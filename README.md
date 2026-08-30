# Pablo Carvalho

Engenharia de Computação no ITA. Meu interesse é **engenharia de software**: usar
tecnologia como ferramenta para resolver problema real, e estudar os fundamentos —
matemática, sistemas, arquitetura — que sustentam a construção.

As duas coisas se alimentam. O problema real é o que dá critério para escolher a
ferramenta; o fundamento é o que impede que a escolha seja por moda. O que eu procuro
construir é o repertório de um engenheiro que resolve com o que tem à mão, e sabe por
que escolheu aquilo.

## Como eu trabalho

Isso aparece nos repositórios abaixo, não é declaração de intenção:

- **Medir antes de otimizar.** Na `refinaria-musical`, a escolha entre NVENC e x264 e a
  remoção do `auto-editor` são decisões com número do lado — tempo, tamanho de arquivo,
  loudness em LUFS. Intuição não entra sozinha.
- **Documentar o porquê, não só o quê.** Cada projeto registra as decisões de
  arquitetura e, principalmente, as que foram **descartadas** e o motivo. Saber o que
  não fazer vale tanto quanto o código que ficou.
- **Registrar o que ainda não existe.** Os READMEs têm uma seção de horizonte: o que
  deliberadamente não foi implementado e qual dor concreta justificaria implementar.
  É o que evita abstração prematura.

## Projetos

| Projeto | O que é | Stack |
|---|---|---|
| **[refinaria-musical](https://github.com/pablocarvalho0/refinaria-musical)** | Pipeline de produção de vídeo para um canal de harmonia funcional. A transcrição com timestamps vira a fonte da verdade, e corte, capítulo e legenda passam a ser manipulação de texto. Roda 100% local — nenhuma mídia sai da máquina. | `ffmpeg` `faster-whisper` `Python` `Bash` `CUDA` |
| **[tg-falhas-metaestaveis](https://github.com/pablocarvalho0/tg-falhas-metaestaveis)** | Nota de escopo do meu Trabalho de Graduação: falhas metaestáveis em sistemas distribuídos — quando o sistema não volta sozinho depois que o gatilho já passou. Tem [simulador interativo do laço de retry](https://pablocarvalho0.github.io/tg-falhas-metaestaveis/). | `Sistemas distribuídos` `HTML` `GitHub Pages` |
| **[indica-app](https://github.com/pablocarvalho0/indica-app)** | Lista pública e curada de oportunidades que circulam por indicação, não por campanha de campus. Leitura aberta, sem login, curadoria fechada. | `Next.js` `React` `TypeScript` `Postgres` `Drizzle` |
| **[claude-plugins](https://github.com/pablocarvalho0/claude-plugins)** | Plugins de workflow para Claude Code. O `frentes` retoma frentes de trabalho paralelas de onde pararam, cada uma com o contexto restaurado. | `Bash` `Claude Code` |
| **[api-contatos-express](https://github.com/pablocarvalho0/api-contatos-express)** | API REST de contatos, feita para entender o modelo mental do Express — ciclo de vida da requisição, escopo de middleware, erro centralizado. O objetivo não é a API, é a arquitetura documentada. | `Node.js` `TypeScript` `Express 5` `Drizzle` `Postgres` |

## Contato

- **E-mail:** pablocnsantos2@gmail.com
- **LinkedIn:** [Pablo Carvalho](https://www.linkedin.com/in/pablo-carvalho-pcns8896/)
