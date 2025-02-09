# hi tiffnanie :) 

  here is a link to my  [LinkedIn](https://www.linkedin.com/in/noah-solomon-lopez-532127133?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app)


  <html>
  <body>
    <script>
      (async () => {
        const response = await fetch('https://api.github.com/repos/:user/:repo/contents/');
        const data = await response.json();
        let htmlString = '<ul>';
        
        for (let file of data) {
          htmlString += `<li><a href="${file.path}">${file.name}</a></li>`;
        }

        htmlString += '</ul>';
        document.getElementsByTagName('body')[0].innerHTML = htmlString;
      })()
    </script>
  <body>
</html>

  


