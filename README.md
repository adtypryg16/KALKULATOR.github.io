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
