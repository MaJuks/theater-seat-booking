# Teatro — Sistema de Reserva de Poltronas

Sistema web de reserva de assentos para teatro, com visualização interativa das poltronas e persistência de dados no navegador.

---

## Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript (Vanilla)
- Bootstrap 5.2.2
- localStorage (API nativa do navegador)

---

## Instalação e Execução

Não requer instalação de dependências ou servidor backend.

1. Clone o repositório:
   ```bash
   git clone https://github.com/MaJuks/teatro.git
   ```
2. Abra o arquivo `index.html` diretamente no navegador.

---

## Funcionalidades

- Visualização de **240 poltronas** organizadas em 10 fileiras com corredor central
- **Reserva de assento** por número (estado temporário)
- **Confirmação de reserva** — torna o assento permanentemente ocupado
- **Remoção de reserva** — libera um assento ocupado mediante confirmação
- **Persistência de dados** via localStorage — as ocupações são mantidas entre sessões do navegador
- Indicadores visuais de status: disponível, reservada e ocupada

---

## Estrutura do Projeto

```
teatro/
├── index.html        # Estrutura da página
├── js.js             # Lógica da aplicação
├── style.css         # Estilos customizados
└── img/
    ├── logo.jpg          # Logo do teatro
    ├── disponivel.jpg    # Ícone de poltrona disponível
    ├── reservada.jpg     # Ícone de poltrona reservada
    └── ocupada.jpg       # Ícone de poltrona ocupada
```

---

## Informações Acadêmicas

| Campo | Informação |
|---|---|
| Instituição | Instituto Federal do Paraná — Campus Cascavel |
| Curso | Tecnologia da Informação |
| Disciplina | Programação para Internet |
| Professor | Fernando de Lima Alves |
| Período | 2º Semestre de 2022 |
| Atividade | Desenvolvimento de aplicação web interativa utilizando manipulação do DOM e persistência de dados com localStorage |

---

## Autor

**Maria Julia**
Criado em: 13/10/2022

---

## Status do Projeto

Concluido — desenvolvido como atividade avaliativa.
