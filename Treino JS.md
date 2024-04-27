<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Estudo</title>
</head>
<body>

<script language="JavaScript1.5">
    resultado=confirm("Tudo Bem?");
    if (resultado===true)
    {document.write("escolheu OK!");}
    else
    {document.write("Escolheu Cancelar!");}

</script>

<!-- Next -->

<script language="JavaScript1.5">

    resultado=confirm("Tudo Bem?");
        resultado?escreve="Ok!":escreve="Cancelar!";
        document.write("Escolheu "+escreve);

</script>

<!--comando switch -->

<script language="JavaScript1.5">

    resultado=confirm("Tudo Bem?");
    switch(resultado)
      {case true:
      documento.write("escolheu OK");
      break;
      case false:
      document.write("escolheu CANCELAR!");
      break;}

</script>

<!--Laço While-->

<script language="JavaScript1.5">

    i=0;

    while (i<5) {document.write(" i="+i++ +"<BR>");}

</script>

<!--Laço do While -->

<script language="JavaScript1.5">

    i=10;
    while (i<5) {document.write("i="+i++ +"<BR>");}

</script>

<!--Comando For-->

<script language="JavaScript1.5">

    i=2;
    document.write("<P>antes do for i = "+i+"</P>");
    for (i=0; i<5;i++)
    {document.write("i="+i+"<BR>");}
    document.write("<P>depois do for i ="+i+"</P>");

</script>


</body>
</html>