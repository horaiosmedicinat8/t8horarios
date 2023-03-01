<b> Hoje é:
<HTML>
	<HEAD><TITLE>Exibir Data e Hora em HTML </TITLE>
		<script src="https://code.jquery.com/jquery-1.11.2.js"></script>
		<script type="text/javascript">
			jQuery(window).load(function($){
				atualizaRelogio();
			});
		</script>
	</HEAD>
	<BODY>
		<div>
			<output id="data" style="font-family: 'arial black', 'avant garde'; font-size: 24px;"></output>
		</div>
		<div>
			<output id="hora" style="font-family: 'arial black', 'avant garde'; font-size: 24px;"></output>				
		</div>			
	</BODY>
	<script>
		function atualizaRelogio(){ 
			var momentoAtual = new Date();
			
			var vhora = momentoAtual.getHours();
			var vminuto = momentoAtual.getMinutes();
			var vsegundo = momentoAtual.getSeconds();
			
			var vdia = momentoAtual.getDate();
			var vmes = momentoAtual.getMonth() + 1;
			var vano = momentoAtual.getFullYear();
			
			if (vdia < 10){ vdia = "0" + vdia;}
			if (vmes < 10){ vmes = "0" + vmes;}
			if (vhora < 10){ vhora = "0" + vhora;}
			if (vminuto < 10){ vminuto = "0" + vminuto;}
			if (vsegundo < 10){ vsegundo = "0" + vsegundo;}

			dataFormat = vdia + " / " + vmes + " / " + vano;
			horaFormat = vhora + " : " + vminuto + " : " + vsegundo;

			document.getElementById("data").innerHTML = dataFormat;
			document.getElementById("hora").innerHTML = horaFormat;

			setTimeout("atualizaRelogio()",1000);
		}
	</script>	
</HTML>

<style>
  table {
    border-collapse: collapse;
    width: 100%;
  }

  th, td {
    border: 1px solid black;
    padding: 8px;
    text-align: left;
  }

  th {
    background-color: #ddd;
  }

  tr:nth-child(even) {
    background-color: #f2f2f2;
  }
</style>

<!DOCTYPE html>
<html>
  <head>
    <title>Horarios Medicina T8 - Semana 1 (20/03 - 24/03)</title>
    <style>
      table {
        border-collapse: collapse;
        width: 100%;
      }

      th, td {
        border: 1px solid black;
        padding: 8px;
        text-align: center;
      }

      th {
        background-color: #ddd;
      }

      tr:nth-child(even) {
        background-color: #836FFF;
      }
    </style>
  </head>
  <body>
    <h1>Horarios Medicina T8</h1>
    <h2>Semana 1 (20/03 - 24/03)</h2>
    <table>
      <tr>
        <th>Horário</th>
        <th>Segunda-feira dia 20</th>
        <th>Terça-feira dia 21</th>
        <th>Quarta-feira dia 22</th>
        <th>Quinta-feira dia 23</th>
        <th>Sexta-feira dia 24</th>
      </tr>
      <tr>
        <td>8:20 - 10:00</td>
        <td rowspan="2">PB II</td>
        <td rowspan="2"> MORFO II</td>
        <td rowspan="2">SACO II</td>
        <td rowspan="2">MORFO II</td>
        <td rowspan="2">SACO II</td>
      </tr>
      <tr>
        <td>10:20 - 12:00</td>
      </tr>
      <tr>
        <td>13:30 - 15:10</td>
        <td rowspan="2"> </td>
        <td rowspan="2">PB II</td>
        <td rowspan="2">MORFO II</td>
        <td rowspan="2"></td>
        <td rowspan="2">MORFO II</td>
      </tr>
      <tr>
        <td>15:20 - 17:00</td>
      </tr>
      <tr>
        <td>19:00 - 20:40</td>
        <td rowspan="2"> Seminario Int. II</td>
        <td rowspan="2">HFS</td>
        <td rowspan="2">Meio Amb. Ecoc. e Soc.</td>
        <td rowspan="2"></td>
        <td rowspan="2"></td>
      </tr>
      <tr>
        <td>20:50 - 22:40</td>
      </tr>
    </table>
  </body>
</html>

<!DOCTYPE html>
<html>
  <head>
    <title>  Semana 2 (27/03 - 31/03)</title>
    <style>
      table {
        border-collapse: collapse;
        width: 100%;
      }

      th, td {
        border: 1px solid black;
        padding: 8px;
        text-align: center;
      }

      th {
        background-color: #ddd;
      }

      tr:nth-child(even) {
        background-color: #836FFF;
      }
    </style>
  </head>
  <body>
       <h2> Semana 2 (27/03 - 31/03)</h2>
    <table>
      <tr>
        <th>Horário</th>
        <th>Segunda-feira dia 27</th>
        <th>Terça-feira dia 28</th>
        <th>Quarta-feira dia 29</th>
        <th>Quinta-feira dia 30</th>
        <th>Sexta-feira dia 31</th>
      </tr>
      <tr>
        <td>8:20 - 10:00</td>
        <td rowspan="2">PB II</td>
        <td rowspan="2"> MORFO II</td>
        <td rowspan="2">SACO II</td>
        <td rowspan="2">MORFO II</td>
        <td rowspan="2">SACO II</td>
      </tr>
      <tr>
        <td>10:20 - 12:00</td>
      </tr>
      <tr>
        <td>13:30 - 15:10</td>
        <td rowspan="2"> </td>
        <td rowspan="2">PB II</td>
        <td rowspan="2">MORFO II</td>
        <td rowspan="2"></td>
        <td rowspan="2">MORFO II</td>
      </tr>
      <tr>
        <td>15:20 - 17:00</td>
      </tr>
      <tr>
        <td>19:00 - 20:40</td>
        <td rowspan="2"> Seminario Int. II</td>
        <td rowspan="2">HFS</td>
        <td rowspan="2">Meio Amb. Ecoc. e Soc.</td>
        <td rowspan="2"></td>
        <td rowspan="2"></td>
      </tr>
      <tr>
        <td>20:50 - 22:40</td>
      </tr>
    </table>
  </body>
</html>

<!DOCTYPE html>
<html>
  <head>
    <title> Semana 3 (03/04 - 07/04)</title>
    <style>
      table {
        border-collapse: collapse;
        width: 100%;
      }

      th, td {
        border: 1px solid black;
        padding: 8px;
        text-align: center;
      }

      th {
        background-color: #ddd;
      }

      tr:nth-child(even) {
        background-color: #f2f2f2;
      }
    </style>
  </head>
  <body>
       <h2>Semana 3 (03/04 - 07/04)</h2>
    <table>
      <tr>
        <th>Horário</th>
        <th>Segunda-feira dia 03</th>
        <th>Terça-feira dia 04</th>
        <th>Quarta-feira dia 05</th>
        <th>Quinta-feira dia 06</th>
        <th>Sexta-feira dia 07</th>
      </tr>
      <tr>
        <td>8:20 - 10:00</td>
        <td rowspan="2">PB II</td>
        <td rowspan="2"> MORFO II</td>
        <td rowspan="2">SACO II</td>
        <td rowspan="2">MORFO II</td>
        <td rowspan="2">FERIADO</td>
      </tr>
      <tr>
        <td>10:20 - 12:00</td>
      </tr>
      <tr>
        <td>13:30 - 15:10</td>
        <td rowspan="2"> </td>
        <td rowspan="2">PB II</td>
        <td rowspan="2">MORFO II</td>
        <td rowspan="2"></td>
        <td rowspan="2">FERIADO</td>
      </tr>
      <tr>
        <td>15:20 - 17:00</td>
      </tr>
      <tr>
        <td>19:00 - 20:40</td>
        <td rowspan="2"> Seminario Int. II</td>
        <td rowspan="2">HFS</td>
        <td rowspan="2">Meio Amb. Ecoc. e Soc.</td>
        <td rowspan="2"></td>
        <td rowspan="2">FERIADO</td>
      </tr>
      <tr>
        <td>20:50 - 22:40</td>
      </tr>
    </table>
  </body>
</html>

<!DOCTYPE html>
<html>
  <head>
    <title> Semana 4 (10/04 - 14/04)</title>
    <style>
      table {
        border-collapse: collapse;
        width: 100%;
      }

      th, td {
        border: 1px solid black;
        padding: 8px;
        text-align: center;
      }

      th {
        background-color: #ddd;
      }

      tr:nth-child(even) {
        background-color: #f2f2f2;
      }
    </style>
  </head>
  <body>
       <h2>Semana 4 (10/04 - 14/04)</h2>
    <table>
      <tr>
        <th>Horário</th>
        <th>Segunda-feiradia 10</th>
        <th>Terça-feira dia 11</th>
        <th>Quarta-feira dia12</th>
        <th>Quinta-feira dia 13</th>
        <th>Sexta-feira dia 14</th>
      </tr>
      <tr>
        <td>8:20 - 10:00</td>
        <td rowspan="2">PB II</td>
        <td rowspan="2"> MORFO II</td>
        <td rowspan="2">SACO II</td>
        <td rowspan="2">MORFO II</td>
        <td rowspan="2">SACO II</td>
      </tr>
      <tr>
        <td>10:20 - 12:00</td>
      </tr>
      <tr>
        <td>13:30 - 15:10</td>
        <td rowspan="2"> </td>
        <td rowspan="2">PB II</td>
        <td rowspan="2">MORFO II</td>
        <td rowspan="2"></td>
        <td rowspan="2">MORFO II</td>
      </tr>
      <tr>
        <td>15:20 - 17:00</td>
      </tr>
      <tr>
        <td>19:00 - 20:40</td>
        <td rowspan="2"> Seminario Int. II</td>
        <td rowspan="2">HFS</td>
        <td rowspan="2">Meio Amb. Ecoc. e Soc.</td>
        <td rowspan="2"></td>
        <td rowspan="2"></td>
      </tr>
      <tr>
        <td>20:50 - 22:40</td>
      </tr>
    </table>
  </body>
</html>

<!DOCTYPE html>
<html>
  <head>
    <title> Semana 5 (17/04 -21/04)</title>
    <style>
      table {
        border-collapse: collapse;
        width: 100%;
      }

      th, td {
        border: 1px solid black;
        padding: 8px;
        text-align: center;
      }

      th {
        background-color: #ddd;
      }

      tr:nth-child(even) {
        background-color: #f2f2f2;
      }
    </style>
  </head>
  <body>
       <h2>Semana 5 (17/04 -21/04))</h2>
    <table>
      <tr>
        <th>Horário</th>
        <th>Segunda-feiradia 17</th>
        <th>Terça-feira dia 18</th>
        <th>Quarta-feira dia 19</th>
        <th>Quinta-feira dia 20</th>
        <th>Sexta-feira dia 21</th>
      </tr>
      <tr>
        <td>8:20 - 10:00</td>
        <td rowspan="2">PB II</td>
        <td rowspan="2"> MORFO II</td>
        <td rowspan="2">SACO II</td>
        <td rowspan="2">MORFO II</td>
        <td rowspan="2">FERIADO</td>
      </tr>
      <tr>
        <td>10:20 - 12:00</td>
      </tr>
      <tr>
        <td>13:30 - 15:10</td>
        <td rowspan="2"> </td>
        <td rowspan="2">PB II</td>
        <td rowspan="2">MORFO II</td>
        <td rowspan="2"></td>
        <td rowspan="2">FERIADO</td>
      </tr>
      <tr>
        <td>15:20 - 17:00</td>
      </tr>
      <tr>
        <td>19:00 - 20:40</td>
        <td rowspan="2"> </td>
        <td rowspan="2">HFS</td>
        <td rowspan="2">Meio Amb. Ecoc. e Soc.</td>
        <td rowspan="2"></td>
        <td rowspan="2">FERIADO</td>
      </tr>
      <tr>
        <td>20:50 - 22:40</td>
      </tr>
    </table>
  </body>
</html>

<!DOCTYPE html>
<html>
  <head>
    <title> Semana 6 (24/04 -28/04)</title>
    <style>
      table {
        border-collapse: collapse;
        width: 100%;
      }

      th, td {
        border: 1px solid black;
        padding: 8px;
        text-align: center;
      }

      th {
        background-color: #ddd;
      }

      tr:nth-child(even) {
        background-color: #f2f2f2;
      }
    </style>
  </head>
  <body>
       <h2>Semana 6 (24/04 -28/04)</h2>
    <table>
      <tr>
        <th>Horário</th>
        <th>Segunda-feira dia 24</th>
        <th>Terça-feira dia 25</th>
        <th>Quarta-feira dia 26</th>
        <th>Quinta-feira dia 27</th>
        <th>Sexta-feira dia 28</th>
      </tr>
      <tr>
        <td>8:20 - 10:00</td>
        <td rowspan="2">PB II</td>
        <td rowspan="2"> MORFO II</td>
        <td rowspan="2">SACO II</td>
        <td rowspan="2">MORFO II</td>
        <td rowspan="2">SACO II</td>
      </tr>
      <tr>
        <td>10:20 - 12:00</td>
      </tr>
      <tr>
        <td>13:30 - 15:10</td>
        <td rowspan="2"> </td>
        <td rowspan="2">PB II</td>
        <td rowspan="2">MORFO II</td>
        <td rowspan="2"></td>
        <td rowspan="2">MORFO II</td>
      </tr>
      <tr>
        <td>15:20 - 17:00</td>
      </tr>
      <tr>
        <td>19:00 - 20:40</td>
        <td rowspan="2"> </td>
        <td rowspan="2">HFS</td>
        <td rowspan="2">Meio Amb. Ecoc. e Soc.</td>
        <td rowspan="2"></td>
        <td rowspan="2"></td>
      </tr>
      <tr>
        <td>20:50 - 22:40</td>
      </tr>
    </table>
  </body>
</html>

<!DOCTYPE html>
<html>
  <head>
    <title> Semana 7 (01/05 -05/05)</title>
    <style>
      table {
        border-collapse: collapse;
        width: 100%;
      }

      th, td {
        border: 1px solid black;
        padding: 8px;
        text-align: center;
      }

      th {
        background-color: #ddd;
      }

      tr:nth-child(even) {
        background-color: #f2f2f2;
      }
    </style>
  </head>
  <body>
       <h2>Semana 7 (01/05 -05/05)</h2>
    <table>
      <tr>
        <th>Horário</th>
        <th>Segunda-feira dia 01</th>
        <th>Terça-feira dia 02</th>
        <th>Quarta-feira dia 03</th>
        <th>Quinta-feira dia 04</th>
        <th>Sexta-feira dia 05</th>
      </tr>
      <tr>
        <td>8:20 - 10:00</td>
        <td rowspan="2">FERIADO</td>
        <td rowspan="2"> MORFO II</td>
        <td rowspan="2">SACO II</td>
        <td rowspan="2">MORFO II</td>
        <td rowspan="2">SACO II</td>
      </tr>
      <tr>
        <td>10:20 - 12:00</td>
      </tr>
      <tr>
        <td>13:30 - 15:10</td>
        <td rowspan="2">FERIADO</td>
        <td rowspan="2">PB II</td>
        <td rowspan="2">MORFO II</td>
        <td rowspan="2"></td>
        <td rowspan="2">MORFO II</td>
      </tr>
      <tr>
        <td>15:20 - 17:00</td>
      </tr>
      <tr>
        <td>19:00 - 20:40</td>
        <td rowspan="2">FERIADO</td>
        <td rowspan="2">HFS</td>
        <td rowspan="2">Meio Amb. Ecoc. e Soc.</td>
        <td rowspan="2"></td>
        <td rowspan="2"></td>
      </tr>
      <tr>
        <td>20:50 - 22:40</td>
      </tr>
    </table>
  </body>
</html>

<!DOCTYPE html>
<html>
  <head>
    <title> Semana 8 (08/05 -12/05)</title>
    <style>
      table {
        border-collapse: collapse;
        width: 100%;
      }

      th, td {
        border: 1px solid black;
        padding: 8px;
        text-align: center;
      }

      th {
        background-color: #ddd;
      }

      tr:nth-child(even) {
        background-color: #f2f2f2;
      }
    </style>
  </head>
  <body>
       <h2>Semana 8 (08/05 -12/05)</h2>
    <table>
      <tr>
        <th>Horário</th>
        <th>Segunda-feira dia 08</th>
        <th>Terça-feira dia 09</th>
        <th>Quarta-feira dia 10</th>
        <th>Quinta-feira dia 11</th>
        <th>Sexta-feira dia 12</th>
      </tr>
      <tr>
        <td>8:20 - 10:00</td>
        <td rowspan="2">PB II</td>
        <td rowspan="2"> MORFO II</td>
        <td rowspan="2">SACO II</td>
        <td rowspan="2">MORFO II</td>
        <td rowspan="2">SACO II</td>
      </tr>
      <tr>
        <td>10:20 - 12:00</td>
      </tr>
      <tr>
        <td>13:30 - 15:10</td>
        <td rowspan="2"> </td>
        <td rowspan="2">PB II</td>
        <td rowspan="2">MORFO II</td>
        <td rowspan="2"></td>
        <td rowspan="2">MORFO II</td>
      </tr>
      <tr>
        <td>15:20 - 17:00</td>
      </tr>
      <tr>
        <td>19:00 - 20:40</td>
        <td rowspan="2"> </td>
        <td rowspan="2">HFS</td>
        <td rowspan="2">Meio Amb. Ecoc. e Soc.</td>
        <td rowspan="2"></td>
        <td rowspan="2"></td>
      </tr>
      <tr>
        <td>20:50 - 22:40</td>
      </tr>
    </table>
  </body>
</html>

<!DOCTYPE html>
<html>
  <head>
    <title> Semana 9 (15/05 -19/05)</title>
    <style>
      table {
        border-collapse: collapse;
        width: 100%;
      }

      th, td {
        border: 1px solid black;
        padding: 8px;
        text-align: center;
      }

      th {
        background-color: #ddd;
      }

      tr:nth-child(even) {
        background-color: #f2f2f2;
      }
    </style>
  </head>
  <body>
       <h2>Semana 9 (15/05 -19/05)</h2>
    <table>
      <tr>
        <th>Horário</th>
        <th>Segunda-feira dia 15</th>
        <th>Terça-feira dia 16</th>
        <th>Quarta-feira dia 17</th>
        <th>Quinta-feira dia 18</th>
        <th>Sexta-feira dia 19</th>
      </tr>
      <tr>
        <td>8:20 - 10:00</td>
        <td rowspan="2">PB II</td>
        <td rowspan="2"> MORFO II</td>
        <td rowspan="2">SACO II</td>
        <td rowspan="2">MORFO II</td>
        <td rowspan="2">SACO II</td>
      </tr>
      <tr>
        <td>10:20 - 12:00</td>
      </tr>
      <tr>
        <td>13:30 - 15:10</td>
        <td rowspan="2"> </td>
        <td rowspan="2">PB II</td>
        <td rowspan="2">MORFO II</td>
        <td rowspan="2"></td>
        <td rowspan="2">MORFO II</td>
      </tr>
      <tr>
        <td>15:20 - 17:00</td>
      </tr>
      <tr>
        <td>19:00 - 20:40</td>
        <td rowspan="2"> </td>
        <td rowspan="2">HFS</td>
        <td rowspan="2">Meio Amb. Ecoc. e Soc.</td>
        <td rowspan="2"></td>
        <td rowspan="2"></td>
      </tr>
      <tr>
        <td>20:50 - 22:40</td>
      </tr>
    </table>
  </body>
</html>

<!DOCTYPE html>
<html>
  <head>
    <title> Semana 10 (22/05 -27/05)</title>
    <style>
      table {
        border-collapse: collapse;
        width: 100%;
      }

      th, td {
        border: 1px solid black;
        padding: 8px;
        text-align: center;
      }

      th {
        background-color: #ddd;
      }

      tr:nth-child(even) {
        background-color: #f2f2f2;
      }
    </style>
  </head>
  <body>
       <h2>Semana 10 (22/05 -27/05)</h2>
    <table>
      <tr>
        <th>Horário</th>
        <th>Segunda-feira dia 22</th>
        <th>Terça-feira dia 23</th>
        <th>Quarta-feira dia 24</th>
        <th>Quinta-feira dia 25</th>
        <th>Sexta-feira dia 26</th>
      </tr>
      <tr>
        <td>8:20 - 10:00</td>
        <td rowspan="2">PB II</td>
        <td rowspan="2"> MORFO II</td>
        <td rowspan="2">SACO II</td>
        <td rowspan="2">MORFO II</td>
        <td rowspan="2">SACO II</td>
      </tr>
      <tr>
        <td>10:20 - 12:00</td>
      </tr>
      <tr>
        <td>13:30 - 15:10</td>
        <td rowspan="2"> </td>
        <td rowspan="2">PB II</td>
        <td rowspan="2">MORFO II</td>
        <td rowspan="2"></td>
        <td rowspan="2">MORFO II</td>
      </tr>
      <tr>
        <td>15:20 - 17:00</td>
      </tr>
      <tr>
        <td>19:00 - 20:40</td>
        <td rowspan="2"> </td>
        <td rowspan="2">HFS</td>
        <td rowspan="2">Meio Amb. Ecoc. e Soc.</td>
        <td rowspan="2"></td>
        <td rowspan="2"></td>
      </tr>
      <tr>
        <td>20:50 - 22:40</td>
      </tr>
    </table>
  </body>
</html>

<!DOCTYPE html>
<html>
  <head>
    <title> Semana 11 (29/05 -02/06)</title>
    <style>
      table {
        border-collapse: collapse;
        width: 100%;
      }

      th, td {
        border: 1px solid black;
        padding: 8px;
        text-align: center;
      }

      th {
        background-color: #ddd;
      }

      tr:nth-child(even) {
        background-color: #f2f2f2;
      }
    </style>
  </head>
  <body>
       <h2>Semana 11 (29/05 -02/06)</h2>
    <table>
      <tr>
        <th>Horário</th>
        <th>Segunda-feira dia 29</th>
        <th>Terça-feira dia 30</th>
        <th>Quarta-feira dia 31</th>
        <th>Quinta-feira dia 01</th>
        <th>Sexta-feira dia 02</th>
      </tr>
      <tr>
        <td>8:20 - 10:00</td>
        <td rowspan="2">PB II</td>
        <td rowspan="2"> MORFO II</td>
        <td rowspan="2">SACO II</td>
        <td rowspan="2">MORFO II</td>
        <td rowspan="2">SACO II</td>
      </tr>
      <tr>
        <td>10:20 - 12:00</td>
      </tr>
      <tr>
        <td>13:30 - 15:10</td>
        <td rowspan="2"> </td>
        <td rowspan="2">PB II</td>
        <td rowspan="2">MORFO II</td>
        <td rowspan="2"></td>
        <td rowspan="2">MORFO II</td>
      </tr>
      <tr>
        <td>15:20 - 17:00</td>
      </tr>
      <tr>
        <td>19:00 - 20:40</td>
        <td rowspan="2"> </td>
        <td rowspan="2">HFS</td>
        <td rowspan="2">Meio Amb. Ecoc. e Soc.</td>
        <td rowspan="2"></td>
        <td rowspan="2"></td>
      </tr>
      <tr>
        <td>20:50 - 22:40</td>
      </tr>
    </table>
  </body>
</html>

<!DOCTYPE html>
<html>
  <head>
    <title> Semana 12 (05/06 -09/06)</title>
    <style>
      table {
        border-collapse: collapse;
        width: 100%;
      }

      th, td {
        border: 1px solid black;
        padding: 8px;
        text-align: center;
      }

      th {
        background-color: #ddd;
      }

      tr:nth-child(even) {
        background-color: #f2f2f2;
      }
    </style>
  </head>
  <body>
       <h2>Semana 12 (05/06 -09/06)</h2>
    <table>
      <tr>
        <th>Horário</th>
        <th>Segunda-feira dia 05</th>
        <th>Terça-feira dia 06</th>
        <th>Quarta-feira dia 07</th>
        <th>Quinta-feira dia 08</th>
        <th>Sexta-feira dia 09</th>
      </tr>
      <tr>
        <td>8:20 - 10:00</td>
        <td rowspan="2">PB II</td>
        <td rowspan="2"> MORFO II</td>
        <td rowspan="2">SACO II</td>
        <td rowspan="2">FERIADO</td>
        <td rowspan="2">SACO II</td>
      </tr>
      <tr>
        <td>10:20 - 12:00</td>
      </tr>
      <tr>
        <td>13:30 - 15:10</td>
        <td rowspan="2"> </td>
        <td rowspan="2">PB II</td>
        <td rowspan="2">MORFO II</td>
        <td rowspan="2">FERIADO</td>
        <td rowspan="2">MORFO II</td>
      </tr>
      <tr>
        <td>15:20 - 17:00</td>
      </tr>
      <tr>
        <td>19:00 - 20:40</td>
        <td rowspan="2"> </td>
        <td rowspan="2">HFS</td>
        <td rowspan="2">Meio Amb. Ecoc. e Soc.</td>
        <td rowspan="2">FERIADO</td>
        <td rowspan="2"></td>
      </tr>
      <tr>
        <td>20:50 - 22:40</td>
      </tr>
    </table>
  </body>
</html>

<!DOCTYPE html>
<html>
  <head>
    <title> Semana 13 (12/06 -16/06)</title>
    <style>
      table {
        border-collapse: collapse;
        width: 100%;
      }

      th, td {
        border: 1px solid black;
        padding: 8px;
        text-align: center;
      }

      th {
        background-color: #ddd;
      }

      tr:nth-child(even) {
        background-color: #f2f2f2;
      }
    </style>
  </head>
  <body>
       <h2>Semana 13 (12/06 -16/06)</h2>
    <table>
      <tr>
        <th>Horário</th>
        <th>Segunda-feira dia 12</th>
        <th>Terça-feira dia 13</th>
        <th>Quarta-feira dia 14</th>
        <th>Quinta-feira dia 15</th>
        <th>Sexta-feira dia 16</th>
      </tr>
      <tr>
        <td>8:20 - 10:00</td>
        <td rowspan="2">PB II</td>
        <td rowspan="2"> MORFO II</td>
        <td rowspan="2">SACO II</td>
        <td rowspan="2">MORFO II</td>
        <td rowspan="2">SACO II</td>
      </tr>
      <tr>
        <td>10:20 - 12:00</td>
      </tr>
      <tr>
        <td>13:30 - 15:10</td>
        <td rowspan="2"> </td>
        <td rowspan="2">PB II</td>
        <td rowspan="2">MORFO II</td>
        <td rowspan="2"></td>
        <td rowspan="2">MORFO II</td>
      </tr>
      <tr>
        <td>15:20 - 17:00</td>
      </tr>
      <tr>
        <td>19:00 - 20:40</td>
        <td rowspan="2"> </td>
        <td rowspan="2">HFS</td>
        <td rowspan="2">Meio Amb. Ecoc. e Soc.</td>
        <td rowspan="2"></td>
        <td rowspan="2"></td>
      </tr>
      <tr>
        <td>20:50 - 22:40</td>
      </tr>
    </table>
  </body>
</html>

<!DOCTYPE html>
<html>
  <head>
    <title> Semana 14 (19/06 -23/06)</title>
    <style>
      table {
        border-collapse: collapse;
        width: 100%;
      }

      th, td {
        border: 1px solid black;
        padding: 8px;
        text-align: center;
      }

      th {
        background-color: #ddd;
      }

      tr:nth-child(even) {
        background-color: #f2f2f2;
      }
    </style>
  </head>
  <body>
       <h2>Semana 14 (19/06 -23/06)</h2>
    <table>
      <tr>
        <th>Horário</th>
        <th>Segunda-feira dia 19</th>
        <th>Terça-feira dia 20</th>
        <th>Quarta-feira dia 21</th>
        <th>Quinta-feira dia 22</th>
        <th>Sexta-feira dia 23</th>
      </tr>
      <tr>
        <td>8:20 - 10:00</td>
        <td rowspan="2">PB II</td>
        <td rowspan="2"> MORFO II</td>
        <td rowspan="2">SACO II</td>
        <td rowspan="2">MORFO II</td>
        <td rowspan="2">SACO II</td>
      </tr>
      <tr>
        <td>10:20 - 12:00</td>
      </tr>
      <tr>
        <td>13:30 - 15:10</td>
        <td rowspan="2"> </td>
        <td rowspan="2">PB II</td>
        <td rowspan="2">MORFO II</td>
        <td rowspan="2"></td>
        <td rowspan="2">MORFO II</td>
      </tr>
      <tr>
        <td>15:20 - 17:00</td>
      </tr>
      <tr>
        <td>19:00 - 20:40</td>
        <td rowspan="2"> </td>
        <td rowspan="2">HFS</td>
        <td rowspan="2">Meio Amb. Ecoc. e Soc.</td>
        <td rowspan="2"></td>
        <td rowspan="2"></td>
      </tr>
      <tr>
        <td>20:50 - 22:40</td>
      </tr>
    </table>
  </body>
</html>

<!DOCTYPE html>
<html>
  <head>
    <title> Semana 15 (26/06 -01/07)</title>
    <style>
      table {
        border-collapse: collapse;
        width: 100%;
      }

      th, td {
        border: 1px solid black;
        padding: 8px;
        text-align: center;
      }

      th {
        background-color: #ddd;
      }

      tr:nth-child(even) {
        background-color: #f2f2f2;
      }
    </style>
  </head>
  <body>
       <h2> Semana 15 (26/06 -01/07)</h2>
    <table>
      <tr>
        <th>Horário</th>
        <th>Segunda-feira dia 26</th>
        <th>Terça-feira dia 27</th>
        <th>Quarta-feira dia 28</th>
        <th>Quinta-feira dia 29</th>
        <th>Sexta-feira dia 30</th>
      </tr>
      <tr>
        <td>8:20 - 10:00</td>
        <td rowspan="2">PB II</td>
        <td rowspan="2"> MORFO II</td>
        <td rowspan="2">SACO II</td>
        <td rowspan="2">MORFO II</td>
        <td rowspan="2">SACO II</td>
      </tr>
      <tr>
        <td>10:20 - 12:00</td>
      </tr>
      <tr>
        <td>13:30 - 15:10</td>
        <td rowspan="2"> </td>
        <td rowspan="2">PB II</td>
        <td rowspan="2">MORFO II</td>
        <td rowspan="2"></td>
        <td rowspan="2">MORFO II</td>
      </tr>
      <tr>
        <td>15:20 - 17:00</td>
      </tr>
      <tr>
        <td>19:00 - 20:40</td>
        <td rowspan="2"> </td>
        <td rowspan="2">HFS</td>
        <td rowspan="2">Meio Amb. Ecoc. e Soc.</td>
        <td rowspan="2"></td>
        <td rowspan="2"></td>
      </tr>
      <tr>
        <td>20:50 - 22:40</td>
      </tr>
    </table>
  </body>
</html>

<!DOCTYPE html>
<html>
  <head>
    <title> Semana 16 (03/07 - 07/07)</title>
    <style>
      table {
        border-collapse: collapse;
        width: 100%;
      }

      th, td {
        border: 1px solid black;
        padding: 8px;
        text-align: center;
      }

      th {
        background-color: #ddd;
      }

      tr:nth-child(even) {
        background-color: #f2f2f2;
      }
    </style>
  </head>
  <body>
       <h2>Semana 16 (03/07 - 07/07)</h2>
    <table>
      <tr>
        <th>Horário</th>
        <th>Segunda-feira dia 03</th>
        <th>Terça-feira dia 04</th>
        <th>Quarta-feira dia 05</th>
        <th>Quinta-feira dia 06</th>
        <th>Sexta-feira dia 07</th>
      </tr>
      <tr>
        <td>8:20 - 10:00</td>
        <td rowspan="2">PB II</td>
        <td rowspan="2"> MORFO II</td>
        <td rowspan="2">SACO II</td>
        <td rowspan="2">MORFO II</td>
        <td rowspan="2">SACO II</td>
      </tr>
      <tr>
        <td>10:20 - 12:00</td>
      </tr>
      <tr>
        <td>13:30 - 15:10</td>
        <td rowspan="2"> </td>
        <td rowspan="2">PB II</td>
        <td rowspan="2">MORFO II</td>
        <td rowspan="2"></td>
        <td rowspan="2">MORFO II</td>
      </tr>
      <tr>
        <td>15:20 - 17:00</td>
      </tr>
      <tr>
        <td>19:00 - 20:40</td>
        <td rowspan="2"> </td>
        <td rowspan="2">HFS</td>
        <td rowspan="2">Meio Amb. Ecoc. e Soc.</td>
        <td rowspan="2"></td>
        <td rowspan="2"></td>
      </tr>
      <tr>
        <td>20:50 - 22:40</td>
      </tr>
    </table>
  </body>
</html>

<!DOCTYPE html>
<html>
  <head>
    <title> Semana 17 (10/07 - 14/07)</title>
    <style>
      table {
        border-collapse: collapse;
        width: 100%;
      }

      th, td {
        border: 1px solid black;
        padding: 8px;
        text-align: center;
      }

      th {
        background-color: #ddd;
      }

      tr:nth-child(even) {
        background-color: #f2f2f2;
      }
    </style>
  </head>
  <body>
       <h2>Semana 17 (10/07 - 14/07)</h2>
    <table>
      <tr>
        <th>Horário</th>
        <th>Segunda-feira dia 10</th>
        <th>Terça-feira dia 11</th>
        <th>Quarta-feira dia 12</th>
        <th>Quinta-feira dia 13</th>
        <th>Sexta-feira dia 14</th>
      </tr>
      <tr>
        <td>8:20 - 10:00</td>
        <td rowspan="2">PB II</td>
        <td rowspan="2"> MORFO II</td>
        <td rowspan="2">SACO II</td>
        <td rowspan="2">MORFO II</td>
        <td rowspan="2">SACO II</td>
      </tr>
      <tr>
        <td>10:20 - 12:00</td>
      </tr>
      <tr>
        <td>13:30 - 15:10</td>
        <td rowspan="2"> </td>
        <td rowspan="2">PB II</td>
        <td rowspan="2">MORFO II</td>
        <td rowspan="2"></td>
        <td rowspan="2">MORFO II</td>
      </tr>
      <tr>
        <td>15:20 - 17:00</td>
      </tr>
      <tr>
        <td>19:00 - 20:40</td>
        <td rowspan="2"> </td>
        <td rowspan="2">HFS</td>
        <td rowspan="2">Meio Amb. Ecoc. e Soc.</td>
        <td rowspan="2"></td>
        <td rowspan="2"></td>
      </tr>
      <tr>
        <td>20:50 - 22:40</td>
      </tr>
    </table>
  </body>
</html>

<!DOCTYPE html>
<html>
  <head>
    <title> Semana 18 (17/07 - 21/07)</title>
    <style>
      table {
        border-collapse: collapse;
        width: 100%;
      }

      th, td {
        border: 1px solid black;
        padding: 8px;
        text-align: center;
      }

      th {
        background-color: #ddd;
      }

      tr:nth-child(even) {
        background-color: #f2f2f2;
      }
    </style>
  </head>
  <body>
       <h2>Semana 18 (17/07 - 21/07)</h2>
    <table>
      <tr>
        <th>Horário</th>
        <th>Segunda-feira dia 17</th>
        <th>Terça-feira dia 18</th>
        <th>Quarta-feira dia 19</th>
        <th>Quinta-feira dia 20</th>
        <th>Sexta-feira dia 21</th>
      </tr>
      <tr>
        <td>8:20 - 10:00</td>
        <td rowspan="2">PB II</td>
        <td rowspan="2"> MORFO II</td>
        <td rowspan="2">SACO II</td>
        <td rowspan="2">MORFO II</td>
        <td rowspan="2">SACO II</td>
      </tr>
      <tr>
        <td>10:20 - 12:00</td>
      </tr>
      <tr>
        <td>13:30 - 15:10</td>
        <td rowspan="2"> </td>
        <td rowspan="2">PB II</td>
        <td rowspan="2">MORFO II</td>
        <td rowspan="2"></td>
        <td rowspan="2">MORFO II</td>
      </tr>
      <tr>
        <td>15:20 - 17:00</td>
      </tr>
      <tr>
        <td>19:00 - 20:40</td>
        <td rowspan="2"> </td>
        <td rowspan="2">HFS</td>
        <td rowspan="2">Meio Amb. Ecoc. e Soc.</td>
        <td rowspan="2"></td>
        <td rowspan="2"></td>
      </tr>
      <tr>
        <td>20:50 - 22:40</td>
      </tr>
    </table>
  </body>
</html>
