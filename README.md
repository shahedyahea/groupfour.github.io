<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cloud Computing</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f4f6f9;
            color: #333;
            line-height: 1.6;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #0277bd;
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        h1, h2 {
            font-family: 'Verdana', sans-serif;
            text-transform: uppercase;
            font-weight: bold;
        }

        section {
            margin: 30px;
            padding: 20px;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }

        section img {
            width: 100%;
            border-radius: 8px;
            margin-top: 20px;
        }

        footer {
            background-color: #0277bd;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 30px;
        }

        .container {
            display: flex;
            justify-content: space-between;
            flex-wrap: wrap;
        }

        .content {
            width: 48%;
            margin-bottom: 20px;
        }

        .content ul {
            list-style: square;
            margin-left: 20px;
        }

        .content ul li {
            margin-bottom: 10px;
        }

        .image-container {
            display: flex;
            justify-content: space-around;
            margin-top: 20px;
        }

        .image-container img {
            width: 48%;
            border-radius: 8px;      

        }

        @media screen and (max-width: 768px) {
            .container {
                flex-direction: column;
            }

            .content {
                width: 100%;
            }

            .image-container img {
                width: 100%;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Cloud Computing</h1>
    <p>Understanding Cloud Computing, its Benefits, and Models</p>
</header>

<section>
    <h2>What is Cloud Computing?</h2>
    <p>Cloud computing is the delivery of computing services like servers, storage, databases, networking, software, and more over the internet (cloud). It enables businesses and individuals to access technology resources without needing to own or maintain physical infrastructure.</p>
    <div class="image-container">
        <img src="c2.jpg" alt="Cloud Computing Concept">
    </div>
</section>

<section>
    <h2>Benefits of Cloud Computing</h2>
    <div class="container">
        <div class="content">
            <h3>Why use Cloud Computing?</h3>
            <ul>
                <li>Cost-Efficiency: Reduces the need for physical hardware and maintenance costs.</li>
                <li>Scalability: Easily adjust resources to meet changing demands.</li>
                <li>Global Access: Access cloud services from anywhere with an internet connection.</li>
            </ul>
        </div>
        <div class="content">
            <h3>Other Advantages</h3>
            <ul>
                <li>Improved Collaboration: Teams can work together online in real-time.</li>
                <li>Security: Advanced encryption and security protocols help protect data.</li>
                <li>Automatic Updates: Cloud services handle software and security updates automatically.</li>
            </ul>
        </div>
    </div>
</section>

<section>
    <h2>Advantages and Disadvantages  of Cloud Computing</h2>
    <div class="container">
        <div class="content">
            <h3>Advantages</h3>
            <ul>
                <li>Flexible and scalable on-demand services.</li>
                <li>Cost-effective: Pay only for what you use.</li>
                <li>Disaster Recovery: Cloud services often provide automatic backups and recovery options.</li>
            </ul>
        </div>
        <div class="content">
            <h3>Disadvantages</h3>
            <ul>
                <li>Security and Privacy concerns: Sensitive data might be vulnerable to attacks.</li>
                <li>Internet Connectivity: Dependent on a stable internet connection for access.</li>
                <li>Limited Control: You rely on third-party service providers for your cloud services.</li>
            </ul>
        </div>
    </div>
    <div class="image-container">
        <img src="pc.jpg" alt="Pros and Cons of Cloud Computing">
    </div>
</section>

<section>
    <h2>Cloud Service Models</h2>
    <p>There are three main service models in cloud computing:</p>
    <ul>
        <li><strong>IaaS (Infrastructure as a Service)</strong>: Provides virtualized computing resources such as storage and servers.</li>
        <li><strong>PaaS (Platform as a Service)</strong>: Offers a platform allowing customers to develop, run, and manage applications without worrying about infrastructure.</li>
        <li><strong>SaaS (Software as a Service)</strong>: Delivers software applications over the internet on a subscription basis.</li>
    </ul>
    <div class="image-container">
        <img src="mcs.jpg" alt="Cloud Computing service model">
    </div>
</section>

<footer>
    <p>&copy; 2024 Cloud Computing Second Division Fourth Group</p>
</footer

</body>
</html>
