# Estudo de comandos NASM 
<p align="center">
<img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAOEAAADhCAMAAAAJbSJIAAAArlBMVEX///8AN2QALl8AMmEAJ1sANGLv8/YAK10AKVwAJVoAMGAAF1Q6WHsAIFjr8PP6+/w7X4FyhJsxU3jS2eCltcO1vslpgZoAGlWDmq6ZpbVNZ4W6xNBEXX2fr791iqGUp7lQb40AAEsAAEPG0dpcdZEAPmvg5+0AAEeMnrF7kKbZ4ObL1N0ADlEAGFSkrrtEZ4gaTHUoW4FWephvjaYAElIeTXUmSXCFn7Rgco0fRGyc8L0zAAAIKElEQVR4nO2aa3eiOhRAIQECqQGLgFSq0OFRwfbq3KlO/f9/7AYICorTdqx9rHv2h642RMzmJCcPKkkAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA8L/FyhaB6/wzz71k+XOVyog9Pdzd39//uH9g8urn8t9f/u+pE48y67Nb+ja0bBG7c2+5kjFGRFcMDhuP0XaYXM9DJ4gL7bOb+JdYZla4fjKxt6pi6AhjFVNi6Kk98fJpnJlaK1KWZppZVhTFKA4C13Udx3HdIAgWI16WZWan8lfA0uIwf7ZlQyGUm8myTImubu3Id0eFuatlaVnshP7Me54M7C2vYzBWRlipKWPNmILUdG3fRs/XOQ/4SLOsz5YtnHmyYoaCaKUmq1Q3xmToB4udmmTGzk2eDFIupOgEUUpVjnxEWYoxRYiQUpix8dUTWi29+TQoPsPNGgX5T/7QCRWNVcuorLybYOeW8REZrdjYMHReq9eJC3GfcqgykvLoDZdRFCVJ4nn8RxQth/Y6xezh/sd47f3DY/pRdtkojDayTvCuqVg3ts+5Y4o+ZXL9aJNifeffEcOUEoUZ6nYw8WZ+lX9MreyRVrdXihJL4/kr4D08z2e/g1Fm9jbqvbDMhR9tdL3VcqyjzcRfCDstc2aRTY3eqKkYKQofopPEd2KeVN6cUvhg5pnogoqLeZKydlxUQvAwbAadFlSjEuE+N6Ijmg69KZ8Bv+iEUTgJ7dpRZbzyA9HczM3XY0Pv6ZUq4tknXc6d+LLd6yzM2F+hTusxMmTPyerLhettaWtY7mtRwujgOgy+aNQEZuBtUKf5vMfZ1yJn8nF5m/JprGfIGaqd/I7Nr23He1+yNTpdTyV0ky+qZlum420Ncjzs+PBMbc8tvnC33LMmXT1G8rjOgMXN0lCOxx0mfNTlnzNJ/w0RaelRluZxXR7n8pjQo9hRna1z91uETpAr+9gYqRdU0dMW+YaS466J2CqZfrPNkNNEUCV4UmdOq8gHpEdPwYPZV54O+olFDsFEno2qEjOcGMezAl/VrMPR9wpeRYZwFb7x0K1abwURU47GHtUfl83E+M3QVrgafXmdFhczWe/RI9H02/VNgZUQLjCo2286k+PcgvngDL9ZZmmT8xV0VCfPLF8zhBTU8UNo43/HsbcjvLry6uwiWXG8WCxi11P0XfgUlsSf28BzcRW/6p5a6LRKQ73OPWzpfOfolZjzauGZ+durkGvyTWe9wR3ZCBubvFmS8d13xe5z2jGHtz5Ro/rNbNF6hJ3ykndYzFe3L2aprurcMF/b9uC2WtEUg4Gzz52hPeDYSd0ay5kMjrhN3NZ9s/nz7WGNTdleq/rVbnHruZWIOU1u7S6bnC9GnkNndp7kyNPL7FkaegRzkBHxr2w/W8lXygMyNKwXcxGjWD0EU+btntuMbzKPqlxVhohWR20tELMDSZqmBsUHkGv+idyh9By/OGJ16qwMRRYl24Opz69Wdbg29BS5HxbWtbOt3nd5XBn2nFjJ6qOfGD0XUGkYurF/ht9yt3ZpG8po0FVsG476zgvrhm7r7rY+WjC8YMi/8PjcoDE8h0VE923pGMp60smhbUPXOCHIg1hlJo/0X/2TYT9nGmZJZ9/XNZT1zuhuGzqnOik3LCfWUX8EP95Q23Qf9YGhrExfMNRbkJbhTPxBlAPuzJYhEoWdJbCKdFGMzze0ht21mTqedw3lp9Zaps/Qme4Jyd5wU7dOmTsHTK29IZqJwpuE7b4R49lUFE/w2YbdwaISmpsHhqq8P4I5NlTlzvMa7wzNbeVA5ieebG1o7CfPoDkCooP93uwanWs47+RzIl/XOaITV7pPqC8ZanvDLK0Ng9caSqIDyErrUOtsw2DcNlE8cW9h2EwHJPkLQ62OIY1ebZiJTyStaucajlrTK2XRqCmvDdWNLWYnpUmobzCUBiJLpNEOb7oLT4+hdFuV6TfvZ5htdvMrZtFif6E2pFGmiyeghK8zbI1DKRTzZfluTYB0PSr+YIjf2VBbNsNN1e2gPbMLwwnfU4kaenzCUJaL0Z7Y2BuKTncASp2PM0yaNEq2YXd7sjOU5qIO3hanDFkLEbbKUAp7lwSYuB9l6IsG0Kv88Ghpb7hbXlNbO2HYQ20oJb3rOpW1ZvxLGjqP9SM1Jscngy1Da9ksTZZvNpRy1rdyQ96HGMbV/KoqtttzsWW43yGQ2ZsN+Z6MGAQ1NFO6Yn6AYVGlUYrnvecDbUOpaN4VsumbDSWrcPLZr1nFL0/kHsO5vKE1QGUAl6P+yx1DyW0ykrKYv9Wwy6LuDiS/vOGEt5SkfR20x3A3s+FNhI8MVdIC/dnQEgvp2cUNc4NnmNnpA6xZ17CsX9uIFzevWtP00KxVLx5DR1H1wYkVca+hFXV2IK80LOI4Dto4w7qX6tMLG8aYIv+PJ5CHhnwrhN9u6F0ZXXRxk/KQ45KGWWqkJ3rRSUOpaB+Bvdawu7feQcuPX9BQS9mLh3LHhmL+fBfDp3KNfzlDa2gvXqzUYyi5e8XzDJVcuqhh7r3iHUCfoRTgZiyeY6iKw7uLGTrOy3VOGEqjVPw3zV8bqliRxdHdpQy1172g9u6uOA+Dg2LLiVJWXliXhtOq0tNj5/4/yrKr+9rwqdpRXTU8MnU5bXqQ9VSV3bUNNw9VUfvs6rn6krv2wQYAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAfCD/AYfyuThoURafAAAAAElFTkSuQmCC" width=200 height=200 > 
</p>


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