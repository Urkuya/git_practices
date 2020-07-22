<!DOCTYPE html>
<html lang="en">
<head>
  <title>Personal Project: HTML table references</title>
  <link href="./styles.css" type="text/css" rel="stylesheet"
</head>

<body>
    <header>
        <h1 class="title">HTML table references</h1>        
        <nav>
            <h2 class="tags">Table Tags</h2>
        </nav>
    </header>
    
    <table class="table">
      <thead class="th"> 
          <th>Tag</th>
          <th>Name</th>
          <th>Description</th>
       </thead>
       <tbody>
         <tr>
          <td><span class="code">&lt;table&gt;</span>
          </td>
          <td>Table</td>
          <td>The wrapper element for all HTML tables.</td>
        </tr>
        <tr>
            <td><span class="code">&lt;thead&gt;</thead></span></td>
            <td>Table Head</td>
            <td>The set of rows defining the column headers in a table.</td>
        </tr>
        <tr>
            <td><span class="code">&lt;tbody&gt;</span></td>
            <td>Table Body</td>
            <td>The set of rows containing actual table data.</td>
        </tr>
        <tr>
            <td><span class="code">&lt;tr&gt;</span></td>
            <td>Table Row</td>
            <td>The table row container.</td>
        </tr>
        <tr> 
            <td><span class="code">&lt;td&gt;</span></td>
            <td>Table Data</td>
            <td>The table row container.</td>
        </tr>
        <tr>
            <td><span class="code">&lt;tfoot&gt;</span></td>
            <td>Table Foot</td>
            <td>The set of rows defining the footer in a table.</td>
        </tr>
      </tbody>
    </table>

       
    <h2 class="attributes">Table Attributes</h2>

    <table>
        <thead>
        <th>Attribute</th>
        <th>Name</th>
        <th>Description</th>
    </thead> 

    <tbody>
      <tr>
          <td><span class="code">&lt;colspan&gt;</span></td>
          <td>Column Span</td>
          <td>Defnines how many columns a td element should span.</td>
      </tr>
      <tr>
          <td><span class="code">&lt;rowspan&gt;</span></td>
          <td>Row Span</td>
          <td>Defines how many rows a td element should span.</td>
      </tr>
    </tbody>
    </table>
</body>

      <tfoot>
        <h4 class="published"><em>Published by Saadat</em></h4>
      </tfoot>
   
</html>