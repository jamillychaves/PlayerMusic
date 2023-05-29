  # Altura e largura em um lugar só CSS
  padding: 50px 38px;

  # Especificidade 
  '#' - contem especificade 100, por esse motivo o '.player' não altera nada no '#player-1' apenas nos outros que não tem nenhum padding definido anteriormente, porém se posteriormente for definido um padding nos outros dois '#player-*' o que está definido no '.player' será ignorado pela especificade da '#' ser 100 e a do '.' ser 10.
  
# O que quer dizer '#' e '.' ?
- a '#' é utilizada para se referir a um id definido no HTML do seu código;
- o '.' é utilizado para se referir a uma class definida no HTML do seu código;

# Como selecionar mais de uma linha para escrever ou modificar algo?
- aperte a tecla ALT e vá selecionando onde irá deixar o cursor para que ao digitar/apagar seja alterado em todos os lugares onde se encontra o cursor.

# Como criar uma div com class  ou id de uma forma rápida?
- digite em seu código '.(nome da class)' e ta pronto o sorvetinho.
- para colocar com id, é o mesmo procedimento, porém com '#'

# Para que serve o alt="" no img?
- o alt="" quer dizer uma forma alternativa do navegador dizer o que seria aquela imagem, caso a mesma não carregue na página.