# Gulahmed
My Personal Portfolio 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gul Ahmed - SEO Expert & LinkSuits Digital Founder</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #e0e0e0;
            background: #0a0e27;
        }

        header {
            background: linear-gradient(135deg, #0a0e27 0%, #1a1535 100%);
            color: white;
            padding: 60px 20px;
            text-align: center;
            box-shadow: 0 2px 10px rgba(0,0,0,0.3);
        }

        header h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
            font-weight: 700;
            color: #fff;
        }

        header .tagline {
            font-size: 1.3em;
            margin-bottom: 20px;
            opacity: 0.95;
            font-weight: 300;
            color: #a78fde;
        }

        header .subtitle {
            font-size: 1.1em;
            opacity: 0.9;
            color: #e0e0e0;
        }

        nav {
            background: #1a1535;
            padding: 15px 0;
            position: sticky;
            top: 0;
            box-shadow: 0 2px 5px rgba(0,0,0,0.2);
            z-index: 100;
        }

        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            gap: 30px;
            flex-wrap: wrap;
            padding: 0 20px;
        }

        nav a {
            text-decoration: none;
            color: #a78fde;
            font-weight: 600;
            font-size: 0.95em;
            transition: color 0.3s;
        }

        nav a:hover {
            color: #d4a5ff;
        }

        .container {
            max-width: 1100px;
            margin: 0 auto;
            padding: 0 20px;
        }

        section {
            background: #1a1535;
            margin: 30px auto;
            padding: 50px;
            border-radius: 8px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.3);
            border: 1px solid #3d2d5f;
        }

        h2 {
            color: #a78fde;
            font-size: 2em;
            margin-bottom: 30px;
            border-bottom: 3px solid #a78fde;
            padding-bottom: 10px;
        }

        h3 {
            color: #d4a5ff;
            font-size: 1.3em;
            margin-top: 25px;
            margin-bottom: 15px;
        }

        .metrics {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            margin-bottom: 40px;
        }

        .metric-card {
            background: linear-gradient(135deg, #1a1535 0%, #2d1f47 100%);
            padding: 30px;
            border-radius: 8px;
            text-align: center;
            border-left: 4px solid #a78fde;
            border: 1px solid #3d2d5f;
        }

        .metric-card .number {
            font-size: 2.5em;
            font-weight: 700;
            color: #a78fde;
            margin-bottom: 10px;
        }

        .metric-card .label {
            color: #e0e0e0;
            font-weight: 600;
            font-size: 0.95em;
        }

        .about-content {
            font-size: 1.05em;
            line-height: 1.8;
            color: #d0d0d0;
        }

        .expertise-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 25px;
            margin-top: 30px;
        }

        .expertise-card {
            background: #1a1535;
            padding: 25px;
            border-radius: 8px;
            border-top: 4px solid #a78fde;
            border: 1px solid #3d2d5f;
        }

        .expertise-card h4 {
            color: #a78fde;
            margin-bottom: 15px;
            font-size: 1.1em;
        }

        .expertise-card ul {
            list-style: none;
            margin-left: 0;
        }

        .expertise-card li {
            padding: 8px 0;
            color: #d0d0d0;
            padding-left: 20px;
            position: relative;
        }

        .expertise-card li:before {
            content: "✓";
            position: absolute;
            left: 0;
            color: #a78fde;
            font-weight: bold;
        }

        .clients-section {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }

        .client-card {
            background: linear-gradient(135deg, #1a1535 0%, #2d1f47 100%);
            padding: 25px;
            border-radius: 8px;
            text-align: center;
            border: 1px solid #3d2d5f;
        }

        .client-card h4 {
            color: #a78fde;
            margin-bottom: 10px;
            font-size: 1.1em;
        }

        .client-card p {
            color: #d0d0d0;
            font-size: 0.95em;
        }

        .cta-button {
            display: inline-block;
            background: linear-gradient(135deg, #a78fde 0%, #d4a5ff 100%);
            color: #1a1535;
            padding: 15px 40px;
            border-radius: 5px;
            text-decoration: none;
            font-weight: 600;
            margin-top: 20px;
            transition: transform 0.3s, box-shadow 0.3s;
            border: none;
            cursor: pointer;
            font-size: 1em;
        }

        .cta-button:hover {
            transform: translateY(-2px);
            box-shadow: 0 5px 20px rgba(167, 143, 222, 0.4);
        }

        footer {
            background: linear-gradient(135deg, #0a0e27 0%, #1a1535 100%);
            color: white;
            text-align: center;
            padding: 40px 20px;
            margin-top: 50px;
            border-top: 2px solid #a78fde;
        }

        footer h3 {
            color: #a78fde;
            margin-bottom: 20px;
        }

        .contact-info {
            display: flex;
            justify-content: center;
            gap: 30px;
            flex-wrap: wrap;
            margin-bottom: 20px;
        }

        .contact-info a {
            color: #d4a5ff;
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s;
        }

        .contact-info a:hover {
            color: white;
        }

        .social-links {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 20px;
        }

        .social-links a {
            display: inline-block;
            width: 40px;
            height: 40px;
            background: rgba(255,255,255,0.2);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            text-decoration: none;
            color: white;
            transition: background 0.3s;
        }

        .social-links a:hover {
            background: rgba(255,255,255,0.4);
        }

        .approach-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }

        .approach-card {
            background: #1a1535;
            padding: 25px;
            border-radius: 8px;
            border-left: 4px solid #a78fde;
            border: 1px solid #3d2d5f;
        }

        .approach-card h4 {
            color: #a78fde;
            margin-bottom: 10px;
        }

        .approach-card p {
            color: #d0d0d0;
            font-size: 0.95em;
            line-height: 1.6;
        }

        @media (max-width: 768px) {
            header h1 {
                font-size: 1.8em;
            }

            header .tagline {
                font-size: 1.1em;
            }

            section {
                padding: 30px 20px;
            }

            h2 {
                font-size: 1.5em;
            }

            nav ul {
                gap: 15px;
            }

            nav a {
                font-size: 0.85em;
            }
        }

        .divider {
            text-align: center;
            color: #a78fde;
            font-size: 1.5em;
            margin: 40px 0;
            opacity: 0.3;
        }
    </style>
</head>
<body>
    <header>
        <h1>Gul Ahmed</h1>
        <div class="tagline">Founder, LinkSuits Digital</div>
        <div class="subtitle">I help businesses turn organic search into a predictable source of leads, customers, and revenue</div>
    </header>

    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#expertise">Expertise</a></li>
            <li><a href="#approach">Approach</a></li>
            <li><a href="#clients">Clients</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <div class="container">
        <!-- Key Metrics Section -->
        <section id="metrics">
            <h2>Impact & Results</h2>
            <div class="metrics">
                <div class="metric-card">
                    <div class="number">25+</div>
                    <div class="label">Active Clients</div>
                </div>
                <div class="metric-card">
                    <div class="number">45-65%</div>
                    <div class="label">Avg. Traffic Growth</div>
                </div>
                <div class="metric-card">
                    <div class="number">500+</div>
                    <div class="label">Publisher Network</div>
                </div>
                <div class="metric-card">
                    <div class="number">95%+</div>
                    <div class="label">Client Satisfaction</div>
                </div>
            </div>
        </section>

        <!-- About Section -->
        <section id="about">
            <h2>About Me</h2>
            <div class="about-content">
                <p>I'm the Founder of <strong>LinkSuits Digital</strong>, a results-driven SEO agency focused on delivering measurable business outcomes through strategic organic growth.</p>
                
                <p style="margin-top: 20px;">Over the past <strong>5+ years</strong>, I've helped 25+ businesses across e-commerce, SaaS, and service industries achieve significant organic traffic growth, improve search rankings, and generate qualified leads that actually convert. I work with brands that are serious about scaling—where ROI matters more than vanity metrics.</p>

                <p style="margin-top: 20px;"><strong>My Philosophy:</strong> Real SEO isn't about chasing rankings or gaming algorithms. It's about understanding your business, identifying genuine growth opportunities, and executing strategies that create sustainable, measurable impact. I focus on solving real problems: <em>How do we attract the right customers? How do we build authority? How do we turn organic search into your most reliable revenue source?</em></p>

                <p style="margin-top: 20px;">Currently pursuing an ADP in Business/Commerce at KASBIT while managing global clients across Upwork, Fiverr, and direct partnerships. Passionate about combining technical excellence with business strategy to drive real growth.</p>
            </div>
        </section>

        <!-- Expertise Section -->
        <section id="expertise">
            <h2>My Expertise</h2>
            
            <h3>Core SEO Services</h3>
            <div class="expertise-grid">
                <div class="expertise-card">
                    <h4>Technical SEO</h4>
                    <ul>
                        <li>Site audits & optimization</li>
                        <li>Core Web Vitals</li>
                        <li>Schema markup</li>
                        <li>Site structure</li>
                    </ul>
                </div>

                <div class="expertise-card">
                    <h4>Content Strategy</h4>
                    <ul>
                        <li>Keyword research</li>
                        <li>Content planning</li>
                        <li>SEO copywriting</li>
                        <li>Topic clustering</li>
                    </ul>
                </div>

                <div class="expertise-card">
                    <h4>Link Building & PR</h4>
                    <ul>
                        <li>Authority link building</li>
                        <li>Guest posting</li>
                        <li>Digital PR campaigns</li>
                        <li>Publisher relations</li>
                    </ul>
                </div>

                <div class="expertise-card">
                    <h4>Local & GEO SEO</h4>
                    <ul>
                        <li>Local search optimization</li>
                        <li>Multi-location management</li>
                        <li>GEO-targeted strategies</li>
                        <li>Google Business Profile</li>
                    </ul>
                </div>

                <div class="expertise-card">
                    <h4>Growth Strategy</h4>
                    <ul>
                        <li>Competitive analysis</li>
                        <li>Growth planning</li>
                        <li>Performance tracking</li>
                        <li>ROI optimization</li>
                    </ul>
                </div>

                <div class="expertise-card">
                    <h4>Business Strategy</h4>
                    <ul>
                        <li>Customer acquisition</li>
                        <li>Revenue scaling</li>
                        <li>Financial modeling</li>
                        <li>Conversion optimization</li>
                    </ul>
                </div>
            </div>
        </section>

        <!-- Approach Section -->
        <section id="approach">
            <h2>My Approach</h2>
            <p style="margin-bottom: 30px;">I believe in transparency, data-driven decisions, and partnerships built on measurable results. Here's what sets me apart:</p>
            
            <div class="approach-grid">
                <div class="approach-card">
                    <h4>Data-First</h4>
                    <p>All recommendations are backed by analytics, competitor research, and financial modeling. I focus on metrics that matter to your business.</p>
                </div>

                <div class="approach-card">
                    <h4>Business-Focused</h4>
                    <p>I solve real business problems. Instead of vanity metrics, we focus on qualified leads, customers, and revenue growth.</p>
                </div>

                <div class="approach-card">
                    <h4>Scalable Solutions</h4>
                    <p>Whether you're a startup or scaling enterprise, strategies grow with your business. No one-size-fits-all approaches.</p>
                </div>

                <div class="approach-card">
                    <h4>Transparent</h4>
                    <p>Monthly dashboards showing organic traffic, rankings, backlinks, and ROI. You always know what's working and why.</p>
                </div>
            </div>
        </section>

        <!-- Clients Section -->
        <section id="clients">
            <h2>Who I Work With</h2>
            <p style="margin-bottom: 30px;">I partner with brands and businesses across multiple industries:</p>
            
            <div class="clients-section">
                <div class="client-card">
                    <h4>E-Commerce</h4>
                    <p>Shopify stores, WooCommerce businesses, and product-based companies looking to scale organic sales.</p>
                </div>

                <div class="client-card">
                    <h4>SaaS & Startups</h4>
                    <p>Growth-focused companies needing to establish organic visibility and generate qualified leads.</p>
                </div>

                <div class="client-card">
                    <h4>Digital Agencies</h4>
                    <p>Agencies offering white-label SEO services and partnership opportunities for scale.</p>
                </div>
            </div>

            <p style="margin-top: 30px;"><strong>Notable Partnerships:</strong> I've had the privilege of working with platforms including Getfluence, ContentManager.io, and Linkhouse, delivering strategies focused on long-term business growth.</p>
        </section>

        <!-- CTA Section -->
        <section style="text-align: center;">
            <h2>Ready to Grow?</h2>
            <p style="font-size: 1.1em; margin-bottom: 30px;">Whether you're looking to strengthen your organic presence, scale qualified traffic, or need an SEO audit—I'm always open to conversations with founders, CMOs, and growth leaders serious about results.</p>
            
            <a href="mailto:gulahmedsheikh@gmail.com" class="cta-button">Get In Touch</a>
        </section>
    </div>

    <!-- Footer -->
    <footer id="contact">
        <h3>Let's Connect</h3>
        <div class="contact-info">
            <a href="mailto:gulahmedsheikh@gmail.com">gulahmedsheikh@gmail.com</a>
            <a href="tel:+923016344422">+92 301-6344422</a>
            <a href="https://linkedin.com/in/gulahmed_linksuitsdigital" target="_blank">LinkedIn</a>
        </div>
        
        <p style="margin-top: 20px; opacity: 0.9;">Based in Karachi, Pakistan | Serving Clients Globally</p>
        <p style="margin-top: 10px; font-size: 0.9em; opacity: 0.8;">© 2026 LinkSuits Digital. All rights reserved.</p>
    </footer>
</body>
</html>
