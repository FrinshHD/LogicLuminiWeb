<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Redirecting...</title>
</head>
<body>
    <div id="content"></div>
    <script type="text/javascript">
        // The URL to load the content from
        var newUrl = 'https://logic-wiki.anturnia.net/';

        // Fetch the content of the new URL
        fetch(newUrl)
            .then(response => response.text())
            .then(html => {
                // Create a temporary DOM element to parse the fetched HTML
                var tempDiv = document.createElement('div');
                tempDiv.innerHTML = html;

                // Extract and load all external assets (CSS, JS)
                var scripts = tempDiv.querySelectorAll('script');
                var styles = tempDiv.querySelectorAll('link[rel="stylesheet"]');

                styles.forEach(function(style) {
                    document.head.appendChild(style);
                });

                scripts.forEach(function(script) {
                    var newScript = document.createElement('script');
                    newScript.src = script.src;
                    document.body.appendChild(newScript);
                });

                // Replace the current content with the fetched content
                document.getElementById('content').innerHTML = tempDiv.innerHTML;
            })
            .catch(error => {
                console.error('Error loading the content:', error);
            });
    </script>
</body>
</html>
