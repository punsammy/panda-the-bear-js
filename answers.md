#Hacking Panda the Bear's Resume

<!-- tag name (eg. 'h1')
class name (eg. '.special-class')
id (eg. '#super-special-id')
descendant selectors (eg. 'header h1'). -->

1. $('.profile-image').attr('src','https://placebear.com/400/400');

2.    
$('h1.highlight').text('Amanda');

3.  
$('#employment > .info-title').text('Work Experience');

4.  
$('#time-travel').parent().remove();

5.   
$('body').css('background-color', 'purple');

6.  
$('.highlight').css('color', 'red');

7.   
$('h1').css('font-family', 'monospace');

8.  
$('.action-icon-bg').css('background-color', 'blue');

9.  
$('form').find('input[name="name"]').attr('placeholder', "identify yourself")

10.   
$('form').find('textarea[name="message"]').attr('placeholder', 'State Your Business');

11.   
$('form').find('input[name = "name"]').attr('value', "Your Nemesis");

12.   
$('form').find('input[name = "email"]').attr('value', "koalathebear@gmail.com");

13.   
$('form').find('input[name = "submit"]').attr('value', 'En garde');


#Adding Elements to the DOM
1.    
$("img[alt='Pikachu']").clone().appendTo('.portfolio-container');

<!-- Another way of selecting picture -->
<!-- $('#right-image').children(":first"); -->
<!-- $("img[title='Pikachu']"); -->

2.  
for (var i = 0; i <10; i++) { $("img[alt='Pikachu']").clone().appendTo('.portfolio-container'); }
