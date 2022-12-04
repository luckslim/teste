<!DOCTYPE html>
<html lang="en">
<head>
    <link rel="stylesheet" href="style.css">
  
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        table.calendario-table td{
        border:1px solid #ccc;
        text-align: center;
        cursor: pointer;
        }
        td.day-selected{
	    background: rgb(220,220,220);
        }
        
.wraper-table{
	overflow-x: auto;
}

table{
	font-weight: 300;
	
	margin:20px 0;
	width: 100%;
	border-collapse: collapse;
}

table tr:nth-of-type(1){
	background: #0091ea;
	color: white;
}

table tr{
	border-bottom: 1px solid #ccc;
}

table tr{
	color: #555;
}

table td{
	padding: 8px;
}



table a.btn{
	font-weight: normal;
	font-size: 13px;
	color: white;
	text-decoration: none;
	padding: 4px 6px;
}

a.btn{
	font-weight: normal;
	font-size: 13px;
	color: white;
	text-decoration: none;
	padding: 4px 6px;
}

a.btn.edit{background: #F4B03E;}
a.btn.delete{background: #E05C4E;}
a.btn.order{background: #0091ea;}


 
   
        
        body{
            
            background-image: url(imagens/fundo.jpg);
            background-attachment: fixed;
            background-size: cover;
            background-repeat: no-repeat;
            background-position: center bottom;
        
        }
        header{
            background-color:rgba(255, 255, 255, 0);
            width: 100%;
            height:100px;
            
            
            
        }
    </style>
</head>




<body-adm>
    <header >
        <div class="div-header">
            
            <div class="dropdown2">
                <a href="index.php"><img  class="dropbtn2" width="15%" src="imagens/brasao.png" alt=""></a>
                <div class="dropdown-content2">

                    <a href="adm-user.php"><img width="80%"src="imagens/user.png" alt=""></a>
                    <a href="adm.php"><img width="80%"src="imagens/lista.png" alt=""></a>
                    <a href="#"><img width="80%"src="imagens/calendar.png" alt=""></a>
                    <a href="compras.php"><img width="80%"src="imagens/compras.png" alt=""></a>
                </div>
            
            </div>
        </div>
        
        <div class="div-header">
            
           
        </div>
       

    </header><hr>
    <div class="corpo-adm">
       <h3>Calendário</h3><img  width="6%"src="imagens/calendar.gif" alt="">
       <?php
            //$mes = isset($_GET['mes']) ? (int)$_GET['mes'] : date('m',time());
            //$ano = isset($_GET['ano']) ? (int)$_GET['ano'] : date('Y',time());

            $mes = date('m',time());
            $ano = date('Y',time());

            if($mes > 12)
                $mes = 12;
            if($mes < 1)
                $mes = 1;

            $numeroDias = cal_days_in_month(CAL_GREGORIAN,$mes,$ano);
            $diaInicialdoMes = date('N',strtotime("$ano-$mes-01"));

            $diaDeHoje = date('d',time());



            $diaDeHoje = "$ano-$mes-$diaDeHoje";

            $meses = array('Janeiro','Fevereiro','Março','Abril','Maio','Junho','Julho','agosto','Setembro','Outubro','Novembro','Dezembro');

            //Nome do mês no formato de string!
            $nomeMes = $meses[(int)$mes-1];
        ?>

        <div class="box-content">

            <table class="calendario-table">
                <tr>
                    <td>Domingo</td>
                    <td>Segunda</td>
                    <td>Terça</td>
                    <td>Quarta</td>
                    <td>Quinta</td>
                    <td>Sexta</td>
                    <td>Sabado</td>
                </tr>

                <?php
                    $n = 1;
                    $z = 0;
                    $numeroDias+=$diaInicialdoMes;
                    while ($n <= $numeroDias) {
                        if($diaInicialdoMes == 7 && $z != $diaInicialdoMes){
                            $z = 7;
                            $n = 8;
                        }
                        if($n % 7 == 1){
                            echo '<tr>';
                        }

                        if($z >= $diaInicialdoMes){
                            $dia = $n - $diaInicialdoMes;
                            if($dia < 10){
                                $dia = str_pad($dia, strlen($dia)+1, "0", STR_PAD_LEFT);
                            }
                            $atual = "$ano-$mes-$dia";
                            if($atual != $diaDeHoje){
                            echo "<td dia=\"$atual\">$dia</td>";
                            }else{
                                echo '<td dia="'.$atual.'" class="day-selected">'.$dia.'</td>';
                            }
                        }else{
                            echo "<td></td>";
                            $z++;
                        }
                        if($n % 7 == 0){
                            echo '</tr>';
                        }
                        $n++;
                    }
                ?>
                
            </table>


      


    </div><br>
    

    

</body-adm>
</html>