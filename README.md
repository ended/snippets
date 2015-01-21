| jQuery Code                | Trigger       |
| -------------------------- |:-------------:|
| jQuery Document Ready      | j:dr          |
| jQuery Ajax			     | j:a           |
| jQuery If Exists		     | j:ife         |
| jQuery If Exists Plugin    | j:ifp         |
| jQuery onClick Function    | j:oc          |
| jQuery Each Function       | j:each        |




#####jQuery Document Ready
-----
~~~~~~
$(function(){
	
});
~~~~~~

#####jQuery Ajax
-----
~~~~~~
$.ajax({
  url: '',
  type: 'POST',
  data: { id :  },
  success:function(msg){
  	
  }  
});
~~~~~~

#####jQuery onClick
-----
~~~~~~
$('').on('click',function(){
	
});
~~~~~~

#####jQuery If Exists
-----
~~~~~~
$('').exists(function(){
	
});
~~~~~~

#####jQuery If Exists Plugin
-----
~~~~~~
jQuery.fn.exists = function(func){
	if(this.length>0){
		func();
	}
}
~~~~~~

#####jQuery Each Function
-----
~~~~~~
$.each([], function( index, value ) {
  //Your Code
})
~~~~~~
