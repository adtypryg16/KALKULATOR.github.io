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
