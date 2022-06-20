# Teste Técnico Desenvolvedor(a) Python Júnior

> Você pode usar o problema descrito aqui para exercitar suas habilidades de desenvolvimento, mas a sua solução será avaliada por alguém da Montenegro Labs apenas se você estiver no processo seletivo da vaga de Desenvolvedor(a) Python Júnior.

## PROBLEMA

O setor de contabildade da Montenegro vem procurando cada vez mais soluções para empresas e clientes.

Com o aumento das demandas surgiu a necessidade ficar por dentro das atuais e potenciais mudanças relacionadas a contabilidade, desdos mais novos assuntos até mudanças da legislação.

## SOLUÇÃO

Para auxiliar a Montenegro, você deve desenvolver um web scraping em uma pagina de contabilidade recomendamos a https://www.contabeis.com.br/conteudo/ nele vocẽ encontrara assuntos relacionados a legislação, contabilidade setor finaceiro etc.

Mas fique atento necessitamos somento dos assuntos relacionados a contabilidade, as prioridades são:

- Filtrar somente assuntos relacionados a contabilidade.
- Ser mais especifico possivel no codigo.
- Se possvel nomear as classes funções e variaveis em ingles seguindo o PEP-8
- Trazer somente o titulo, categoria data ou hora de publicação, link da imagem se possvel e link para a publicação atual.
- Retornar o conteúdo como um json trazendo dentro de uma lista além do retorno adicionar tambem a quantidade total de assuntos dentro do mesmo.
- Fazer isso usando uma classe priorizando todos os aspectos de orientação a objetos e descrever o que cada função faz.
- **Surpreenda-nos**

## AVALIAÇÃO

Inicialmente, nós não iremos olhar o seu código. O projeto será testado de forma automatizada e se ele passar nos testes você receberá um e-mail comunicando que irá para a etapa da entrevista técnica.

Como explicado acima, você não passará para a próxima etapa se a sua solução não atender a todos os testes desse arquivo. Use as verificações presentes nele para guiar o desenvolvimento da sua solução.

O JSON de retorno deve ser semelhante a algo como no JSON abaixo fique a vontade para colocar mais propriedades se achar necessarios:
```json
    {
          data: [
            { title: 'TITULO DA POSTAGEM1', category: 'Receita Federal', time: '15:00:02', link: 'https://www.contabeis.com.br/noticias/51495/...' },
            { title: 'TITULO DA POSTAGEM2', category: 'Receita Federal', time: '15:00:02', link: 'https://www.contabeis.com.br/noticias/51495/...' },
            ...
          ],
          size: 15
        }

```
## RECOMENDAÇÕES

- Use Python >= 3.7
- Use o Playwright
- Use a PEP-8 como referência.
- Use Git.
- [Escreva mensagens claras no Git](https://www.git-tower.com/learn/git/ebook/en/command-line/appendix/best-practices).
- Escreva testes unitários!
- Modele os dados com cautela e procure representar as entidades corretamente.
- Siga a documentação do Python e Playwright
- Documente sua aplicação:
  - Descreva sua aplicação e os problemas que ela resolve.
  - Dê instruções de como executar os testes e a sua aplicação.
