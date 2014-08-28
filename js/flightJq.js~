
/*click function to display flight details*/

$("li").click (function(){
display(this);
});


function display(obj)
{

if(obj.id=="d1")
{
document.getElementById("msg").innerHTML=a1;
$("#head1").css("display","none");
$("#message").css("display","block");
$("#d1").css({"background-color":"white","border-top":"red"});
$("#d2").css("background-color","#4682B4");
$("#d3").css("background-color","#4682B4");
$("#d4").css("background-color","#4682B4");
$("#d5").css("background-color","#4682B4");
setTimeout(function(){
$("#message").css("display","none");
$("#head1").css("display","block");
$("#information"+1).css("display","block");},3000
);

$("#information"+2).css("display","none");
$("#information"+3).css("display","none");
$("#information"+4).css("display","none");
$("#information"+5).css("display","none");
}
else if(obj.id=="d2")
{
document.getElementById("msg").innerHTML=b1;
$("#head1").css("display","none");
$("#message").css("display","block");
$("#d2").css({"background-color":"white","border-top":"red"});
$("#d1").css("background-color","#4682B4");
$("#d3").css("background-color","#4682B4");
$("#d4").css("background-color","#4682B4");
$("#d5").css("background-color","#4682B4");
setTimeout(function(){
$("#message").css("display","none");

$("#d2").css("background-color","white");

$("#head1").css("display","block");
$("#information"+2).css("display","block");},3000);

$("#information"+1).css("display","none");
$("#information"+3).css("display","none");
$("#information"+4).css("display","none");
$("#information"+5).css("display","none");

}

else if(obj.id=="d3")
{
document.getElementById("msg").innerHTML=c1;
$("#head1").css("display","none");
$("#message").css("display","block");
$("#d1").css("background-color","#4682B4");
$("#d2").css("background-color","#4682B4");
$("#d4").css("background-color","#4682B4");
$("#d5").css("background-color","#4682B4");

setTimeout(function(){
$("#message").css("display","none");
$("#d3").css("background-color","white");

$("#head1").css("display","block");
$("#information"+3).css("display","block");},2000);

$("#information"+2).css("display","none");
$("#information"+1).css("display","none");
$("#information"+4).css("display","none");
$("#information"+5).css("display","none");
}

else if(obj.id=="d4")
{
document.getElementById("msg").innerHTML=d1;
$("#head1").css("display","none");
$("#message").css("display","block");
$("#d1").css("background-color","#4682B4");
$("#d2").css("background-color","#4682B4");
$("#d3").css("background-color","#4682B4");
$("#d5").css("background-color","#4682B4");

setTimeout(function(){
$("#message").css("display","none");
$("#d4").css("background-color","white");

$("#head1").css("display","block");
$("#information"+4).css("display","block");},3000);

$("#information"+1).css("display","none");
$("#information"+3).css("display","none");
$("#information"+2).css("display","none");
$("#information"+5).css("display","none");

}

else if(obj.id=="d5")
{
document.getElementById("msg").innerHTML=e1;
$("#head1").css("display","none");
$("#message").css("display","block");
$("#d1").css("background-color","#4682B4");
$("#d2").css("background-color","#4682B4");
$("#d3").css("background-color","#4682B4");
$("#d4").css("background-color","#4682B4");
setTimeout(function(){
$("#message").css("display","none");
$("#d5").css("background-color","white");

$("#head1").css("display","block");
$("#information"+5).css("display","block");},3000);

$("#information"+2).css("display","none");
$("#information"+3).css("display","none");
$("#information"+4).css("display","none");
$("#information"+1).css("display","none");
}

}


$(document).ready(function(){	//document ready start

   
 var x= document.getElementsByClassName("cost1");
 var x1=Math.min(x[0].value,x[1].value,x[2].value,x[3].value,x[4].value);
 tip1=x.length;
document.getElementById("info1").innerHTML=tip1;

  for(var i=0;i<tip1;i++)
  {
    if(x[i].value==x1)
    {
      
        document.getElementById(x[i].id).style.backgroundColor="#FF4500";
                
    }
  }





/*Highlight lowest element value for tab 2*/

var x= document.getElementsByClassName("cost2");
 var x1=Math.min(x[0].value,x[1].value,x[2].value);
 tip2=x.length;

document.getElementById("info2").innerHTML=tip2+" "+"Flights";

  for(var i=0;i<tip2;i++)
  {
    if(x[i].value==x1)
    {
      
        document.getElementById(x[i].id).style.backgroundColor="#FF4500";
                
    }
  }




/*Highlight lowest element value for tab 3*/

 var x= document.getElementsByClassName("cost3");
 var x1=Math.min(x[0].value,x[1].value);
 tip3=x.length;

document.getElementById("info3").innerHTML=tip3+" "+"Flights";

  for(var i=0;i<tip3;i++)
  {
    if(x[i].value==x1)
    {
      
       document.getElementById(x[i].id).style.backgroundColor="#FF4500";
                
    }
  }






/*Highlight lowest element value for tab 4*/

 var x= document.getElementsByClassName("cost4");
 var x1=Math.min(x[0].value,x[1].value,x[2].value,x[3].value);
 tip4=x.length;
document.getElementById("info4").innerHTML=tip4+" "+"Flights";
  for(var i=0;i<tip4;i++)

  {

    if(x[i].value==x1)

    {      

       document.getElementById(x[i].id).style.backgroundColor="#FF4500";
              

    }

  }





/*Highlight lowest element value for tab 5*/

 var x= document.getElementsByClassName("cost5");
 var x1=Math.min(x[0].value,x[1].value,x[2].value);
 tip5=x.length;
document.getElementById("info5").innerHTML=tip5+" "+"Flights";
  for(var i=0;i<tip5;i++)
  {
    if(x[i].value==x1)
    {      
       document.getElementById(x[i].id).style.backgroundColor="#FF4500";
              
    }
  }



 var month;
	var d=new Date();
	   var mon=d.getMonth();
    var day=d.getDate();

    var month1 = ["Jan", "Feb", "Mar", "Apr", "May", "Jun", "Jul", "Aug", "Sep", "Oct", "Nov", "Dec"];
    
    a1=month1[mon] + day;
  document.getElementById("date1").innerHTML = month1[mon] + day+"<span>"+tip1+" flights"+"</span>";

     d.setDate(day+1);
     mon=d.getMonth();
     day=d.getDate();
	
    b1=month1[mon] + day;

  document.getElementById("date2").innerHTML = month1[mon] + (day)+"<span>"+tip2+" flights"+"</span>";

 	d.setDate(day+1);
 	mon=d.getMonth();
 	day=d.getDate();
	
    c1=month1[mon] + day;
  document.getElementById("date3").innerHTML = month1[mon]+ (day)+"<span>"+tip3+" flights"+"</span>";
   d.setDate(day+1);
   mon=d.getMonth();
   day=d.getDate();
   
    d1=month1[mon] + day;
  document.getElementById("date4").innerHTML = month1[mon] + (day)+"<span>"+tip4+" flights"+"</span>";
   d.setDate(day+1);
   mon=d.getMonth();
   day=d.getDate();
   
    e1=month1[mon] + day;
  document.getElementById("date5").innerHTML = month1[mon] + (day)+"<span>"+tip5+" flights"+"</span>";



});/*document ready close*/
