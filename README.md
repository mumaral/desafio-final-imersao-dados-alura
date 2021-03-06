# Joana e Clara: um passeio noturno pela ciência de dados

Notebook disponível [aqui](https://github.com/mumaral/desafio-final-imersao-dados-alura/blob/main/Desafio_Final_Murilo.ipynb).

## Sobre o Projeto

Projeto desenvolvido como [desafio final](https://github.com/alura-cursos/imersao-dados-desafio-final) da terceira edição da [imersão dados](https://github.com/alura-cursos/imersaodados3) da Alura, e submetido em 09/05/2021. Nesta edição o foco foi utilizar a ciência de dados para analisar dados farmacológicos, com datasets vindos do desafio: *Mechanisms of Action (MoA) Prediction* do [Kaggle](https://www.kaggle.com/c/lish-moa)

*Este repositório contém apenas o desafio final. As anotações de aulas estão em [outro repositório](https://github.com/mumaral/imersao-dados-alura). Caso você queira abrir o arquivo no Google Collab e não tenha familiaridade com o github, [aqui](https://github.com/mumaral/imersao-dados-alura) está um passo a passo.*

## Resumo

O projeto está escrito em uma linguagem narrativa, que lembra algo como uma crônica, expondo uma conversa entre Clara (mãe) e Joana (sua filha) numa noite de véspera do dia das mãe. Clara trabalha como cientista de dados na área de descobrimento de medicamentos e acaba ensinando e explicando para Joana um pouco do seu trabalho durante a conversa. As células de código (em Python) vão sendo mostradas acompanhando a interação entre mãe e filha, como se fosse a tela do computador da própria Clara.

## Objetivos

- Tentar tornar mais palatável uma apresentação de informações que mistura temas bastante complicados por si só, como farmacologia, genética, estatística e computação. Por isso a escolha da figura da criança e o desafio de explicar conceitos complexos de forma simples.
- Explorar uma faceta mais sutil da ciência de dados: o raciocínio dentro da mente humana.

## Críticas e sugestões

Ficarei feliz em ouvir críticas e sugestões. Fique a vontade para entrar em contato comigo. :smile:

## Reprodutibilidade

**Dados**: presentes no [repositório](https://github.com/alura-cursos/imersaodados3/tree/main/dados) da Alura para a Imersão Dados 2021

**Dependências**: no arquivo [requirements.txt](./requirements.txt)

Exemplo de bash script para rodar no Jupyter com ambiente virtual python (Linux):

```bash
$ git clone https://github.com/mumaral/desafio-final-imersao-dados-alura.git
$ python3 -m venv projectname
$ source projectname/bin/activate
(venv) $ pip3 install -r requirements.txt  
(venv) $ ipython kernel install --user --name=projectname
(venv) $ jupyter lab #kernel -> projectname
```





