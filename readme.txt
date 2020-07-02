Which web event did you hook into to update the display name? 
    function myFunction() {
    var x = document.getElementById("nameinput").value;
    document.getElementById("input").innerHTML = x;

Where in your HTML did you link to your JavaScript file? Are there better places? What's the best place? 
    I have it at the bottom before </body>.  I was told that this is the best place to put the link.

Why is it best practice to store your CSS/JS in external files rather than in your HTML file? 
    neatness and organization. Code in one place looks confusing to me.  CSS/JS can also be reused in 
    other HTML files.