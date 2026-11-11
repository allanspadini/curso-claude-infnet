# Curso de Claude — Pós-graduação em IA e Automação (Infnet)

Repositório com o material do curso de Claude da pós-graduação em **Inteligência Artificial e Automação** da Faculdade Infnet. O curso tem **8 aulas** e cada uma vive na sua própria pasta.

## Público e objetivo

- Alunos de pós-graduação, com perfis variados: nem todos programam no dia a dia. O material precisa funcionar para quem nunca abriu um terminal e ainda ser interessante para quem já programa.
- O foco é **automação com IA na prática**: usar o Claude como ferramenta de trabalho (site, navegador, terminal, API) e construir automações reais, não só conversar com o modelo.
- Cada aula termina com um **projeto prático** que o aluno consegue reproduzir sozinho depois.

## Estrutura do repositório

```
aula-01/ … aula-08/   uma pasta por aula
CLAUDE.md             este arquivo (instruções para o Claude e visão geral do curso)
README.md             apresentação do curso para os alunos
```

Dentro de cada pasta de aula:

- `README.md` — roteiro da aula: objetivos, tópicos, passo a passo da demonstração e o enunciado do projeto prático.
- `projeto/` — código ou arquivos do projeto prático (quando houver).
- `slides/` — material de apresentação (quando houver).
- `exercicios/` — atividades extras e gabaritos (quando houver).

Crie as subpastas só quando tiverem conteúdo; não deixe pastas vazias com `.gitkeep` sem motivo.

## Plano das aulas

| Aula | Tema | Projeto prático |
|------|------|-----------------|
| 1 | Claude no site (claude.ai) e Claude no navegador (extensão Claude in Chrome) | Automação de uma aplicação web feita para o curso — ver [aula-01/README.md](aula-01/README.md) |
| 2 | a definir | a definir |
| 3 | a definir | a definir |
| 4 | a definir | a definir |
| 5 | a definir | a definir |
| 6 | a definir | a definir |
| 7 | a definir | a definir |
| 8 | a definir | a definir |

Atualize esta tabela sempre que o tema ou o projeto de uma aula for definido ou mudar.

## Convenções

- **Idioma**: todo o material para alunos em português do Brasil. Código e identificadores em inglês; comentários e textos de interface em português.
- **Progressão**: cada aula pode usar o que foi visto nas anteriores, nunca o que só vem depois. Ao escrever uma aula, confira as anteriores para não repetir nem pular conteúdo.
- **Reprodutível**: todo passo de demonstração precisa funcionar para o aluno com uma conta comum do Claude. Indique quando algo exigir plano pago, extensão específica ou chave de API.
- **Sem dados reais**: projetos práticos usam dados fictícios. Nada de dados pessoais, credenciais ou automação de sites de terceiros que proíbam robôs nos termos de uso.
- **Projetos web estáticos**: aplicações usadas nos projetos devem rodar sem backend (HTML/CSS/JS puro, abrindo direto no navegador ou publicadas no GitHub Pages), para que qualquer aluno rode sem instalar nada.
- **Recursos do Claude mudam rápido**: ao citar nomes de planos, modelos, botões ou menus, confira a documentação oficial (docs.claude.com / support.claude.com) em vez de confiar na memória, e evite capturas de tela que envelhecem rápido quando um texto resolve.
- **Segurança**: em aulas de agentes e automação no navegador, sempre mostrar os riscos (prompt injection em páginas, permissões por site, revisão humana antes de ações irreversíveis).
