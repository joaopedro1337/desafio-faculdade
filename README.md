## Projeto

<img src="https://i.imgur.com/s3QgA5g.png" alt="Imagem">

> O programa resume-se em um desafio da faculdade, o intuito era criar um programa de cálculo para filmes.
> Usando a linguagem que estamos estudando, Linguagem C.

## 💻 Pré-requisitos

Antes de começar, verifique se você atendeu aos seguintes requisitos:

* Você deve instalar alguma IDE para rodar o programa. <Exemplos: / Dev-C++ / VScode / CodeBlocks / Eclipse.>
* Você tem uma máquina <Windows / Linux / Mac>. Você precisará ter um desses SO instalado em sua máquina.

## 🚀 Instalando <IDES>

Para instalar a IDE, siga estas etapas:

Linux, macOS ou Windows:
```
<Link dos downloads das IDE:

Dev-C++ : encurtador.com.br/BM359
VScode : encurtador.com.br/ixUX7
Codeblocks : encurtador.com.br/GHY38
Eclipse : encurtador.com.br/ehsHO>
```
<Instalando sua IDE de preferência, selecione e use a linguagem C ou C++. >
```
## ☕ Usando o <programa>
  ```


    #include <stdio.h>                   
    #include <locale.h>   
    
    int main ()
    {
        setlocale(LC_ALL, "Portuguese");
        int filme, quantidadeIngresso;
        double valorCompra;
          // Uso do printf para o menu de opções //
        printf ("Olá, bem-vindos ao sistema CALCULO PARA FILMES. O valor do ingresso é : R$ 12.50\n");
        printf ("                                                                             \n");
        printf ("Escolha uma opção de filme:\n");
        printf ("                                                                             \n");
        printf ("- Opção 1 - Vingadores 4.\n");
        printf ("- Opção 2 - Como Treinar o Seu Dragão 3\n");
        printf ("- Opção 3 - Dumbo.\n");
        printf ("- Opção 4 - Shazam.\n");
        printf ("                                                                             \n");
        printf ("                                                                             \n");	
          printf ("Qual opção de filme você deseja? \n");
          scanf("%d", &filme);  
            // Uso do scanf, para leitura dos dados armazenados. //	
        printf ("Informe por gentileza a quantidade de ingressos.\n");
          scanf("%d", &quantidadeIngresso);
            // Uso do scanf, para leitura do valor armazenado. //	
          valorCompra=quantidadeIngresso*12.50;
            // Atribuição //	
        printf ("Para comprar %d ingresso(s) para o filme número %d você irá gastar R$ %2.f reais.", 
        quantidadeIngresso,filme,valorCompra);
        printf ("                                                                             \n");
        printf ("                                                                             \n");
        
        return 0;
        
    }	 	
        >
