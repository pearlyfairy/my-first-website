
<!--Semantic HTML
    gives meaning to our code 
-->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Day 3 Semantic HTML</title>
</head>
<body>
    
    <header>
        <h1> Welcome to my personal space!</h1>        
    </header>

    <main>
        <section> 
            <h2> About Me</h2>
            <p>I can be extrovert and introvert. Schizor? Life is too short. 
                
                <br/> <br/>
            
                The most important thing is to be happy. <br/> <br/>
                How to be happy? Be myself and be empathy. 

            </p>
        </section>
        <section> 
            <h2> Social Media </h2>
            <nav>
                <ul>
                    <li> <a href="https://www.facebook.com/pearly1610"> Facebook </a></li>
                    <li> <a href="https://www.instagram.com/ps_kee/?hl=en"> Instagram </a></li>
                    <li> <a href="https://www.linkedin.com/in/peisan1610"> Linkedin </a></li>                
                </ul>
            </nav>
        </section>
    </main>

    <!-- TABLES-->
    <section> 
        <h2>Exploring neighbour countries</h2>
    <table border=""> 
        <thead> <!--table head-->
            <tr> <!--table row-->
            <th>Country</th> <!--table header-->
            <th>Attraction</th>
            <th>Best food</th>             
        </tr>
    </thead>
    </section> 

    <tbody> <!--table body-->
        <!--rows and cells go here-->
        <tr> 
            <td rowspan="2">Singapore</td> <!--table data-->
            <td>Merlion Park</td>
            <td rowspan="2">Singapore Laksa (Geylang)</td>
        </tr>
        <tr>
            <td>Gardens by the Bay</td>            
        </tr>        
            <td rowspan="3">Thailand</td>
            <td>The Grand Palace</td>
            <td>Duck noodle</td>        
        </tr>
        <tr>
            <td rowspan="3">Big Buddha</td>  
        </tr>
        <tr>
            <td>Fried glass noodle</td>  
        </tr>
       
              
    </tbody>

    <tfoot> <!--table footer-->
        <tr> 
            <td colspan="3">Walk the most and eat the most places</td>
        </tr>
    </tfoot>
    </table>

    <br/>

    <!--adding image using image url-->
    <img src="data:image/jpeg;base64,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" 
    alt="Alternative Text for the image" 
    height="400px" 
    width="500px" 
    />

    <!--adding image from loal folder-->
    <img src="The Grand Palace.jpeg" 
    alt="image is from local folder" 
    height="400px" 
    width="500px" 
    />

    <img src="./images/Garden by the bay.jpeg" 
    alt="image is from local folder" 
    height="400px" 
    width="500px" 
    />

    <br/>    

    <aside>
        <h3>Latest News</h3>
        <p>Working very hard to fit myself to a people leader role.</p>
    </aside>

    <footer>
        <p>&reg; &copy; to myself</p>
    </footer>
</body>
</html>