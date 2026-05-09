# Leena_el-1
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>API Documentation</title>
<link rel="stylesheet" href="style.css">
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
</head>

<body>
<div class="sidebar">
    <div class="logo">
     API <span>Docs</span>
    </div>
    <h3>Documentation</h3>
    <ul>
        <li><a href="#intro">Introduction</a></li>
        <li><a href="#auth">Authentication</a></li>
        <li><a href="#users">Users API</a></li>
        <li><a href="#products">Products API</a></li>
        <li><a href="#orders">Orders API</a></li>
        <li><a href="#errors">Error Codes</a></li>
        <li><a href="#faq">FAQ</a></li>
    </ul>
  </div>
  <div class="main-content">
  <div class="search-box">
  <input type="text" id="searchInput" placeholder="Search documentation...">
  </div>

  <div class="hero">
  <h1>Developer API Documentation</h1>
  <p>
            Build powerful applications using our REST API.
            This documentation provides all endpoints, request methods,
            authentication details, parameters, and response examples
            needed to integrate successfully.
    </p>
    <a href="#intro" class="btn">Get Started</a>
    </div>
    <section class="section" id="intro">
        <h2 class="section-title">Introduction</h2>
        <p>
Welcome to the API documentation portal. This API helps developers manage users,    products, authentication, and orders securely.
        </p>
        <div class="card">
            <h3>Base URL</h3>
            <div class="code-box">
<button class="copy-btn">Copy</button>
<pre><code>https://api.example.com/v1</code></pre>
            </div>
        </div>
 <div class="alert">
 Make sure all requests include the correct authentication token.
    </div>
    </section>
    <section class="section" id="auth">
        <h2 class="section-title">Authentication</h2>
        <p>
            Authentication is performed using API keys.
            Include your API key inside the Authorization header.
        </p>
        <div class="card">
            <h3>Example Request</h3>
            <div class="code-box">
                <button class="copy-btn">Copy</button>
    <pre><code>GET /api/users

    Authorization: Bearer abc123xyz

    Content-Type: application/json</code></pre>
            </div>
        </div>
     </section>
     <section class="section" id="users">
        <h2 class="section-title">Users API</h2>
        <div class="card">
            <h3>Create User</h3>
            <div class="code-box">
                <button class="copy-btn">Copy</button>
   <pre><code>POST /users
   </code></pre>
   </div>
        </div>
    </section>
    <section class="section" id="products">
        <h2 class="section-title">Products API</h2>
        <div class="card">
            <h3>Add Product</h3>
            <div class="code-box">
                <button class="copy-btn">Copy</button>
   <pre><code>POST /products
   </code></pre>
            </div>
        </div>
   <div class="table-container">
           <table border="1" cellspacing="0"
             cellpadding="15" width="50%">
                <tr>
                    <th>Field</th>
                    <th>Type</th>
                    <th>Required</th>
                </tr>
                <tr>
                    <td>title</td>
                    <td>string</td>
                    <td>Yes</td>
                </tr>
                <tr>
                    <td>price</td>
                    <td>number</td>
                    <td>Yes</td>
                </tr>
                <tr>
                    <td>stock</td>
                    <td>number</td>
                    <td>No</td>
                </tr></table>
        </div>
     </section>
     <section class="section" id="orders">
        <h2 class="section-title">Orders API
     </h2>
        <p>
            Order endpoints are used to create,
            track, and manage customer orders.
        </p>
        <div class="card">
            <h3>Create Order</h3>
            <div class="code-box">
                <button class="copy-btn">Copy</button>
     <pre><code>POST /orders
     </code></pre>
            </div></div>
        <div class="card">
            <h3>Track Order</h3>
            <div class="code-box">
                <button class="copy-btn">Copy</button>
     <pre><code>GET /orders/track/1001</code></pre>
            </div>
     </div>
    </section>
    <section class="section" id="errors">
        <h2 class="section-title">Error Codes</h2>
        <p>API errors return standard HTTP status codes.</p>
        <div class="table-container">
<table border="1" cellspacing="0"
                cellpadding="15" width="70%">
                <tr><th>Status Code</th>
                    <th>Meaning</th>
                    <th>Description</th></tr>
                <tr>
     <td>200</td>
                    <td>Success</td>
                    <td>Request completed successfully</td>
                </tr>
                <tr>
     <td>400</td>
                    <td>Bad Request</td>
                    <td>Invalid parameters</td>
                </tr>
                <tr>
     <td>401</td>
                    <td>Unauthorized</td>
      <td>Invalid API key</td></tr>
                <tr><td>404</td>
                    <td>Not Found</td>
                    <td>Requested resource not found</td>
                </tr>
                <tr>
                    <td>500</td>
                    <td>Server Error</td>
                    <td>Internal server issue</td>
                </tr></table>
        </div>
        </section>
 <section class="section" id="faq">
        <h2 class="section-title">Frequently Asked Questions</h2>
        <div class="card">
            <h3>How do I get an API key?</h3>

 <p>
Register on the developer portal and create an application
                to receive your API key.</p>
        </div>
        <div class="card">
            <h3>What format does the API return?</h3>
            <p>All responses are returned in JSON format.</p>
        </div>
        <div class="card">
            <h3>Is HTTPS required?</h3>
            <p>Yes, HTTPS is mandatory for all API requests.</p>
        </div>
    </section>
    <div class="footer">
        <p>© 2026 API Documentation. All Rights Reserved.</p>
    </div>
</div>
</body>
</html>
