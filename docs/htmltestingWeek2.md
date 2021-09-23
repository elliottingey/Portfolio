
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">

  </head>
  <body>

    

<article>
<h1>I didn't realize that a webpage was just a text file</h1>
<h5>By: Elliot Tingey</h5>
  <h6> Last Updated 9/16/21</h6>
<p>I was starting my Portfolio by using the <strong>MarkSheet.io tutorials</strong>
when I found something pretty surprising. I did not realize that there was such
thing as an html file. I was even more surprised to learn that internet browsers
opened and used those files. I knew that CSS could be used in html, but I
had assumed that the html code itself was being run on something else and not just opened in
  html files.</p>


<h3>Bootstrap is super helpful</h3>

<p>Bootstrap drastically improves formatting and visuals. It has been very useful to me. It is now in most of my .md files. An example of 
 its use can be seen blelow. The dog image now fits the page properly and automatically resizes when the browser size changes.</p>		


<h4>This is a (now properly sized) Dog Image</h4>
    
<div>
<img class="img-fluid" src="https://raw.githubusercontent.com/elliottingey/Portfolio/main/docs/images/canine.jpg" alt="Canine">     
</div>


  <h3>Below, I use a bootstrap drop down menu</h3>

<p>This menu is used to see old versions of this webpage. Week 3 and 4 are currently disabled. Eventually,
  This dropdown will be moved to a side column of the site as opposed to below everything else.</p>		
  
  
  
 <div class="fluid-container">
  <h2>Past Versions</h2>
  
  <div class="dropdown">
    <button type="button" class="btn btn-primary dropdown-toggle" data-toggle="dropdown">
      Version History
    </button>
    <div class="dropdown-menu">
      <a class="dropdown-item" href="https://elliottingey.github.io/Portfolio/htmltesting">Week 1</a>
      <a class="dropdown-item" href="https://elliottingey.github.io/Portfolio/htmltestingWeek2">Week 2</a>
      <a class="dropdown-item" href="https://elliottingey.github.io/Portfolio/htmltestingWeek2">Week 3</a>
      <a class="dropdown-item disabled" href="https://elliottingey.github.io/Portfolio/htmltestingWeek4">Week 4</a>
    </div>
  </div>
</div>
    
    
</article>
</body>
</html>
