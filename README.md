<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FlowBoard | Orchestrate Your Team's Success</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet">
    <style>
        /* Basic Reset */
        * { margin: 0; padding: 0; box-sizing: border-box; }
        
        body {
            font-family: 'Inter', sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f9fafb;
        }

        /* Navigation */
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 10%;
            background: #fff;
        }

        .logo { font-weight: 800; font-size: 1.5rem; color: #2563eb; }

        /* Hero Section */
        .hero {
            padding: 80px 10%;
            text-align: center;
            background: linear-gradient(135deg, #ffffff 0%, #eff6ff 100%);
        }

        .hero h1 { font-size: 3rem; margin-bottom: 20px; color: #1e293b; }
        .hero p { font-size: 1.2rem; color: #64748b; max-width: 700px; margin: 0 auto 30px; }
        
        .cta-button {
            background: #2563eb;
            color: white;
            padding: 15px 30px;
            text-decoration: none;
            border-radius: 8px;
            font-weight: 600;
            display: inline-block;
        }

        /* Features Section */
        .features {
            padding: 80px 10%;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
            background: white;
        }

        .feature-card {
            padding: 30px;
            border: 1px solid #e2e8f0;
            border-radius: 12px;
            transition: transform 0.3s ease;
        }

        .feature-card:hover { transform: translateY(-5px); }
        .feature-card h3 { margin-bottom: 15px; color: #1e293b; }

        /* Value Prop Section */
        .value-prop {
            padding: 80px 10%;
            background: #1e293b;
            color: white;
            text-align: center;
        }

        /* Footer */
        footer {
            padding: 40px 10%;
            text-align: center;
            font-size: 0.9rem;
            color: #94a3b8;
        }
    </style>
</head>
<body>

    <nav>
        <div class="logo">FlowBoard</div>
        <div>
            <a href="#" style="text-decoration:none; color:#64748b;">Sign In</a>
        </div>
    </nav>

    <header class="hero">
        <h1>Stop managing tasks. <br><span style="color:#2563eb;">Start orchestrating flow.</span></h1>
        <p>FlowBoard syncs your team's complex workflows into a single, automated visual timeline. No more manual handoffs or missed deadlines.</p>
        <a href="#" class="cta-button">Get Started for Free</a>
    </header>

    <section class="features">
        <div class="feature-card">
            <h3>Visual Workflows</h3>
            <p>Drag-and-drop your entire project lifecycle with intuitive visual maps that everyone understands.</p>
        </div>
        <div class="feature-card">
            <h3>Automated Handoffs</h3>
            <p>When one person finishes, the next is notified instantly with all the context they need to start.</p>
        </div>
        <div class="feature-card">
            <h3>Bottleneck Alerts</h3>
            <p>Our AI identifies where work is piling up before it becomes a problem for your deadline.</p>
        </div>
    </section>

    <section class="value-prop">
        <h2>Built for the Modern Hybrid Team</h2>
        <p style="margin-top:20px; opacity: 0.8;">Whether you're across the desk or across the globe, FlowBoard keeps the momentum moving.</p>
    </section>

    <footer>
        &copy; 2026 FlowBoard Orchestration Tools. Built for the Institute of Product Leadership.
    </footer>

</body>
</html># ai.product-site.
