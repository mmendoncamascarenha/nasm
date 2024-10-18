# Estudo de comandos NASM 
## primeiros comandos

* Programa hello world

```Assembly
global _start 
    section .text
    _start:
        mov rax,1             ; prepara o sistema para fazer a escrita de um texto
        mov rdi,1             ; prepara a saida do texto na tela 
        mov rsi,mensagem      ; imprimir a mensagem na tela
        mov rdx, 13           ; quantidade de caratecteres
        syscall               ; chama o sistema para preparar a saida             
        mov rax, 60           ; executar a saida do sistema 
        xor rdi, rdi          ; executar a saida do sistema
        syscall               ; invocar o sistema operacional para fechar 

        section .data
        mensagem:db 'Hello,Word' ,10        ; O valor 10 representar a quebra de linha 
```