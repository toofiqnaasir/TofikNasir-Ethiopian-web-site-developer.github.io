<!DOCTYPE html>
2   <html lang="en">
3   <head>
4   <meta charset="UTF-8">
5   <meta name="viewport" content="width=device-width, initial-scale=1.0">
6   <title>Tofik Nasir - Ethiopian Web Developer</title>
7   </head>
8   <body>
9   <h1 id="none">TOFIK NASIR WEBSITE DEVELOPER</h1>
10   <nav style="margin-right: 20px;">
11   <ul>
12   <li><a href="#about">ABOUT</a></li>
13   <li><a href="#products">PRODUCTS</a></li>
14   <li><a href="#contact">CONTACT</a></li>
15   </ul>
16   </nav>
17   <section class="hero">
18   <h2>Ethiopian Web Developer Building Your Online Presence</h2>
19   <p>I create simple, interactive websites for small businesses at fair prices.</p>
20   <a href="#contact" class="button">Order Your Website Now!</a>
21   <p>Tofik Nasir Website Developer creates simple and interactive websites for your 
business at fair prices. Order now!</p>
22   </section>
23   <section id="about">
24   <h1>ABOUT THE DEVELOPER</h1>
25   <p>Tofik Nasir is a University  student and certified Business from Arsi University. 
I build websites for <b>hotels, restaurants, barber shops</b>, and many more small 
businesses.</p>
26   </section>
27   <section id="products">
28   <h1>MY PORTFOLIO</h1>
29   <p>Check out some of my recent projects:</p>
30   <figure>
31   <img src="images/travel-agency.png" alt="Travel Agency Website" width="600">
32   <p>Travel Agency Booking System</p>
33   <img src="images/about-me.png" alt="Personal Website" width="600">
34   <p>Personal Portfolio Website</p>
35   <img src="images/restaurant.png" alt="Restaurant Website" width="600">
36   <p>Ethiopian Restaurant Website</p>
37   </figure>
38   <div class="pricing">
39   <h3>Website Packages:</h3>
40   <ul>
41   <li><strong>Basic:</strong> 3-page website - 1,500 ETB</li>
42   <li><strong>Professional:</strong> 5-page + contact form - 3,500 ETB</li>
43   <li><strong>Business:</strong> Mobile-optimized + updates - 4,500 ETB</li>
44   </ul>
45   </div>
46   </section>
47   
48   <section id="contact">
49   <h1>CONTACT ME</h1>
50   <p id="me">Ready for your website? Contact me:</p>
51   <p id="you">Phone: <a href="tel:099370060">0993700060</a></p>
52   <p id="they">Email: <a href="toofiqnaasir52@gmail.com">toofiqnaasir52@gmail.com
</a></p>
53   </section>
54   <footer>
55   &copy; 2026 Tofik Nasir Web Developer - Ethiopian Web Developer
56   </footer>
57   
58   <style>
59       * {
60         margin: 0;
61         padding: 0;
62         box-sizing: border-box;
63         color: goldenrod;
64         text-align: center;
65         font-family: Arial, sans-serif;
66       }
67   
68       body {
69         background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.9));
70         color: white;
71         line-height: 1.6;
72         min-height: 100vh;
73       }
74   
75       #none {
76         text-align: center;
77         text-decoration: underline;
78         text-shadow: 2px 3px #333;
79         color: gold;
80         background: rgba(0, 100, 0, 0.8);
81         padding: 20px;
82         margin: 0;
83       }
84   
85       nav ul {
86         list-style: none;
87         padding: 15px;
88         display: flex;
89         justify-content: center;
90         background: rgba(0,0,0,0.9);
91         margin: 0;
92       }
93   
94       nav li {
95         margin: 0 20px;
96       }
97   
98       nav a {
99         color: gold;
100         text-decoration: none;
101         font-weight: bold;
102         font-size: 1.1em;
103         padding: 5px 10px;
104         border-radius: 3px;
105       }
106   
107       nav a:hover {
108         background: gold;
109         color: black;
110       }
111   
112       .hero {
113         padding: 40px 20px;
114         background: rgba(0, 50, 0, 0.6);
115         margin: 20px auto;
116         max-width: 800px;
117         border-radius: 10px;
118       }
119   
120       .hero h2 {
121         color: gold;
122         margin-bottom: 15px;
123       }
124   
125       .button {
126         background: gold;
127         color: black;
128         padding: 12px 25px;
129         text-decoration: none;
130         border-radius: 5px;
131         display: inline-block;
132         margin: 15px;
133         font-weight: bold;
134         border: 2px solid goldenrod;
135       }
136   
137       .button:hover {
138         background: goldenrod;
139         transform: scale(1.05);
140       }
141   
142       section {
143         padding: 30px 20px;
144         max-width: 900px;
145         margin: 20px auto;
146         background: rgba(0,0,0,0.7);
147         border-radius: 10px;
148       }
149   
150       figure img {
151         width: 90%;
152         max-width: 600px;
153         border: 3px solid gold;
154         border-radius: 10px;
155         margin: 20px auto;
156         display: block;
157         box-shadow: 0 5px 15px rgba(255,215,0,0.3);
158       }
159   
160       .pricing {
161         background: rgba(0, 100, 0, 0.5);
162         padding: 20px;
163         border-radius: 8px;
164         margin-top: 30px;
165       }
166   
167       .pricing ul {
168         list-style: none;
169         margin-top: 15px;
170       }
171   
172       .pricing li {
173         padding: 10px;
174         margin: 5px 0;
175         background: rgba(255,215,0,0.1);
176         border-left: 3px solid gold;
177       }
178   
179       #contact {
180         background: rgba(0, 0, 0, 0.8);
181       }
182   
183       #me { color: gold; font-weight: bold; }
184       #you, #they { margin: 10px 0; }
185   
186       footer {
187         background: black;
188         padding: 20px;
189         margin-top: 40px;
190         border-top: 2px solid gold;
191       }
192   </style>
193   </body>
194   </html>
