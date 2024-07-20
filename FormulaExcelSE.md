<h1 align="center"><strong> Fórmulas Excel SE - Curso CEBRAC </h1></strong>
<strong>Fórmula SE</strong>
<p><b>Observe a tabela:</b></h1></p>

| - | A | B | C |
|----------|----------|----------|----------|
| 1  | Segunda-Feira  | Chuva  | -  |
| 2  | Terça-Feira  | Sol  | -  |
| 3  | Quarta-Feira  | Chuva  | -  |
| 4  | Quinta-Feira  | Sol  | -  |
| 5  | Sexta-Feira  | Sol  | -  |
| 6  | Sábado  | Chuva  | -  |
| 7  | Domingo  | Sol  | -  |

<p>Como fazer a planilha mostrar na coluna C as informações:</p>
<p><b>Chuva</b> = Seriado</p>
<p><b>Sol</b> = Praia</p>

<p><b>Utilizamos a fórmula:</p></b>
<p>=SE(B1="Chuva"; "Seriado"; SE (B1="Sol"; "Praia"; ""))</p>

<p>Onde:</p>
<p><b>=SE</b></p>
<p>Verifica se B1=Chuva; Se sim, Retorna Seriado. Se a primeira condição for falsa, verifica se B1=Sol; Se sim, retorna Praia.</p>
<p>Se ambas forem FALSAS, retorna célula (string) em branco, por isso o "".</p>
<p>O mesmo acontece nas outras células.</p>
