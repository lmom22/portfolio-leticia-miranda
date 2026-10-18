# Letícia Miranda — Portfólio de Automação e Integrações

Portfólio profissional desenvolvido em HTML, CSS e JavaScript, sem dependências de execução. Apresenta a trajetória de transição para tecnologia, um estudo de caso anonimizado de automação de atendimento e uma demonstração interativa de regras de agendamento.

## Conteúdo

- Apresentação profissional e tecnologias utilizadas no projeto.
- Estudo de caso com problema, construção, validação e contribuição pessoal.
- Simulação com unidades, serviços e formas de atendimento fictícios.
- Layout responsivo, navegação por teclado e estilo de impressão.

## Executar localmente

Com Python 3 instalado, execute na raiz do repositório:

```bash
python3 -m http.server 8000 --directory site
```

Abra `http://localhost:8000`. Também é possível abrir `site/index.html` diretamente no navegador.

## Estrutura

| Arquivo | Função |
|---|---|
| `site/index.html` | Conteúdo e estrutura da página |
| `site/style.css` | Layout responsivo e impressão |
| `site/app.js` | Abas e simulação das regras |

## Demonstração e evidências

A demonstração funciona exclusivamente no navegador. Não envia mensagens, não chama APIs, não usa um modelo de IA e não realiza agendamentos. Foi criada para explicar decisões de fluxo; não é uma exportação do chatbot de produção.

O estudo de caso se baseia nas informações do projeto e do currículo da autora. O resultado de 30 para 10 execuções do n8n refere-se a um teste pontual informado no projeto, sem extrapolação para produção. O workflow exportado foi posteriormente inspecionado: contém 55 nós e 13 blocos JavaScript. Prints foram recebidos, mas os originais identificam a instituição no cabeçalho e não integram este repositório.

O desenvolvimento utilizou apoio de IA. A participação da autora no projeto de atendimento está descrita no próprio estudo de caso.

## Verificação

Foram conferidos a sintaxe do JavaScript, os destinos dos links internos, os arquivos locais referenciados e os oito cenários da simulação (cinco permitidos e três restritos). A aparência ainda precisa de inspeção em navegador.

## Privacidade

O repositório contém somente a apresentação e a simulação. Não inclui credenciais, dados de pacientes, identificação do cliente ou configurações da hospedagem original.

## Projeto relacionado

[Workflow de atendimento e agendamento no n8n](https://github.com/lmom22/chatbot-agendamento-n8n). O acesso segue a visibilidade configurada para cada repositório.
