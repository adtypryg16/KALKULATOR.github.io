<h1>CARA MEMBUAT KALKULATOR</h1>
pertama tama kita harus membuat java script dahulu seperti contoh dibawah sini


 function insert(num){
 
	     document.form.textinput.value=document.form.textinput.value + num;
      
		 }
   
	 function clean(){
  
	     document.form.textinput.value="";
      
		 }
   
	 function back(){
  
	     var text= document.form.textinput.value
      
	     document.form.textinput.value= text.substring(0,text.length-1)
      
	     }
      
	 function calculate(){
  
	     var text=document.form.textinput.value
      
		 document.form.textinput.value=eval(text)
   
		 }

na selanjutnya kita memasukan code css supaya tampilan dari program kita bagus dan cantik untuk di lihat
karena dalam pemrograman itu dilihat ui/ux nya contoh css nya seperti dibawah ini:


button{

		     width:80;
			 height:80;
			 border:solid;
			 font-size:25;
			 }
    
		 .textinput{
   
		     width:335;
			 height:50;
			 border:solid;
			 color:black;
			 font-size:25;
			 }
    
		 .main{
   
		     width:350;
		     position:center;
			 border:solid 4px;
			 background:linear-gradient(gray,white);
			 }

Untuk selanjutnya kita lanjut menggunakan code pemrograman html contohnya seperti dibawah ini:

<html>

<head>

</head>

     <body>
     
	 <center>
  
	 <div class=main>
  
	 <h1>KALKULATOR</h1>
  
	 <form name="form">
  
	 <input name="textinput" class="textinput">
  
	 </form>
  
	     <table>
      
		     <tr>
       
			 <td><button onclick="clean()">C</button></td>
			 <td><button onclick="back()">DEL</button></td>
			 <td><button onclick="insert('*')">*</button></td>
			 <td><button onclick="insert('/')">/</button></td>
			 </tr>
			 
			 <tr>
			 <td><button onclick="insert('1')">1</button></td>
			 <td><button onclick="insert('2')">2</button></td>
			 <td><button onclick="insert('3')">3</button></td>
			 <td><button onclick="insert('+')">+</button></td>
			 </tr>
			 
			 <tr>
			 <td><button onclick="insert('4')">4</button></td>
			 <td><button onclick="insert('5')">5</button></td>
			 <td><button onclick="insert('6')">6</button></td>
			 <td><button onclick="insert('-')">-</button></td>
			 </tr>
			 
			 <tr>
			 <td><button onclick="insert('7')">7</button></td>
			 <td><button onclick="insert('8')">8</button></td>
			 <td><button onclick="insert('9')">9</button></td>
			 <td rowspan="2"><button style="height:165" onclick="calculate()">=</button></td>
			 </tr>
			 
			 <tr>
			 <td colspan="2"><button style="width:164" onclick="insert('0')">0</button></td>
			 <td><button onclick="insert('.')">.</button></td>
			 </tr>
			 
	     </table>
      
	 </div>
  
	 </center>
  
	 </body>
  
</html>


![image](https://github.com/adtypryg16/KALKULATOR.github.io/assets/141560118/46777964-9936-43e7-bd83-000957fac0a7)

