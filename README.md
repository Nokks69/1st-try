<!DOCTYPE html>
<html lang="en">
<head>
   
    <title>Self Learn</title>
  
</head>
<body>
<center>
    <header>
        <h1>Welcome to Self Learn</h1>
        <!-- You can add a logo or any introductory text here -->
    </header>
</center>
    <nav>
        <!-- You can add a navigation menu here if you have multiple pages -->
    </nav>

    <main>
        <section>
            <center><h2>Find What You Want To Learn</h2>
            </center> 
            <style>
                /* Add some basic styling for the search bar */
                #search-container {
                    text-align: center;
                    margin: 50px;
                }
        
                #search-input {
                    padding: 10px;
                    width: 300px;
                }
        
                #search-button {
                    padding: 10px;
                }
            </style>
            <!-- Add links, images, or any content related to the featured topic -->
        </section>

       
    </main>
    <div id="search-container">
        <!-- Search input and button -->
        <input type="text" id="search-input" placeholder="Enter your search">
        <button id="search-button" onclick="performSearch()">Search</button>
    </div>

    <div id="search-results">
        <!-- Search results will be displayed here -->
    </div>

    <script>
        // Function to perform the search
        function performSearch() {
            // Get the value from the search input
            var searchTerm = document.getElementById("search-input").value;

            // You can replace this with your actual search logic
            // For simplicity, we'll just display an alert with the search term
            alert("Searching for: " + searchTerm);
        }
    </script>
    <footer>
        <center><p>&copy; 2024 Your Learning Hub. All rights reserved.</p></center>
        <!-- You can add additional footer content or links here -->
    </footer>

</body>
</html>
