# Relatório Individual – Monitor de Clima com Arduino

Relatório individual de extensão sobre o projeto **Monitor de Clima com Arduino: protótipo de IoT para alerta de temperatura e umidade**, desenvolvido em grupo no Centro Universitário FACIMP Wyden (Imperatriz/MA).

O código, os diagramas e a simulação do protótipo estão no repositório do projeto: [emanuelbrno/monitor-clima-arduino](https://github.com/emanuelbrno/monitor-clima-arduino).

## Sobre o projeto

Um Arduino UNO lê temperatura e umidade com o sensor DHT11, envia as leituras ao computador pela USB (Monitor Serial e Plotter Serial da Arduino IDE) e aciona um alerta visual (LED vermelho) e sonoro (buzzer) quando a temperatura atinge o limite configurado. O alarme usa histerese: liga no limite e só desliga 1 °C abaixo.

## O que tem no relatório

- **Contextualização:** o problema, o protótipo e a minha participação (documentação do projeto e redação do relatório coletivo).
- **Metodologia:** local, data, público e etapas da demonstração.
- **Resultados e discussão:** aprendizados, dificuldades e registro fotográfico.
- **Reflexão aprofundada:** a experiência comparada com a teoria do relato coletivo.
- **Considerações finais:** continuidade e soluções alternativas para projetos futuros.

## Registro fotográfico

| | |
| --- | --- |
| ![Equipe na apresentação](docs/foto1%20equipe.jpeg) | ![Leituras no Monitor Serial](docs/foto2%20monitor.png) |
| Equipe na apresentação do protótipo | Leituras no Monitor Serial com o alarme ativo |
| ![Protótipo na protoboard](docs/foto3%20prototipo.jpeg) | ![Demonstração](docs/foto4%20demonstracao.jpeg) |
| Protótipo com o alarme acionado (LED aceso) | Equipe, protótipo e leituras no computador |

## Estrutura

```
relatorio/   relatório individual em .docx e .pdf
docs/        fotos da apresentação do protótipo
README.md    este arquivo
```

## Autoria

- **Discente:** Rebeka Silva Sampaio
- **Professor orientador:** João Lucas
- **Instituição:** Centro Universitário FACIMP Wyden – Imperatriz/MA
- **Ano:** 2026
