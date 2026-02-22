<h1 align="center">📚 SOA Library Management System</h1>

<p align="center">
A comprehensive, full-stack library management solution built for 
<b>Siksha 'O' Anusandhan (SOA) University</b>.
</p>

<p align="center">
Seamless book tracking • Student management • Overdue monitoring • Fine processing
</p>

<hr>

<h2>🚀 Key Features</h2>

<h3>👤 Student Dashboard</h3>
<ul>
  <li><b>Book Discovery:</b> Search and browse the entire library collection.</li>
  <li><b>Personal Tracking:</b> Monitor issued books and return history.</li>
  <li><b>Fine Management:</b> Integrated <b>Razorpay</b> gateway for instant fine payments.</li>
  <li><b>Customization:</b> 6+ premium color themes (Royal Blue, Vibrant Purple, Emerald Green, etc.).</li>
  <li><b>Profile Settings:</b> Manage email, password & profile picture (Avatar support).</li>
  <li><b>Personalized Reports:</b> Download a complete PDF history of library activity.</li>
</ul>

<h3>🛡️ Librarian Console</h3>
<ul>
  <li><b>Issue/Return System:</b> Simplified workflow for managing books.</li>
  <li><b>Overdue Monitor:</b> Real-time tracking with automated & manual notices.</li>
  <li><b>Notice System:</b> Send formal email notifications directly from dashboard.</li>
  <li><b>Stat Insights:</b> View active issues, total students & collection health.</li>
</ul>

<h3>⚙️ Admin Console</h3>
<ul>
  <li><b>Inventory Management:</b> Add, update & remove books.</li>
  <li><b>Student Directory:</b> Full control over student accounts.</li>
  <li><b>Advanced Analytics:</b> Circulation trends, categories & fine statistics.</li>
  <li><b>Global Exports:</b> Export catalog & student list as professional PDFs.</li>
</ul>

<hr>

<h2>🛠️ Technology Stack</h2>

<table>
<tr>
<td><b>Frontend</b></td>
<td>React.js, Tailwind CSS, Lucide React, Framer Motion, Recharts</td>
</tr>
<tr>
<td><b>Backend</b></td>
<td>Node.js, Express.js</td>
</tr>
<tr>
<td><b>Database</b></td>
<td>MongoDB Atlas (Mongoose)</td>
</tr>
<tr>
<td><b>Payments</b></td>
<td>Razorpay API</td>
</tr>
<tr>
<td><b>Notifications</b></td>
<td>Nodemailer (Gmail SMTP)</td>
</tr>
<tr>
<td><b>Reporting</b></td>
<td>jsPDF & AutoTable</td>
</tr>
<tr>
<td><b>Date Handling</b></td>
<td>Day.js</td>
</tr>
</table>

<hr>

<h2>📦 Installation & Setup</h2>

<h3>Prerequisites</h3>
<ul>
  <li>Node.js (v18+)</li>
  <li>MongoDB Atlas Account</li>
  <li>Razorpay API Keys</li>
  <li>Gmail App Password</li>
</ul>

<h3>1️⃣ Clone the Repository</h3>

<pre><code>git clone https://github.com/Anshuman-1234/nexus_p1.git
cd nexus_p1</code></pre>

<h3>2️⃣ Backend Setup</h3>

<pre><code>cd Backend
npm install</code></pre>

<p>Create a <b>.env</b> file in the root directory:</p>

<pre><code>MONGO_URI=your_mongodb_uri
RAZORPAY_KEY_ID=your_key_id
RAZORPAY_KEY_SECRET=your_key_secret
EMAIL_ADDRESS=your_email@gmail.com
EMAIL_PASSWORD=your_app_password</code></pre>

<pre><code>npm start</code></pre>

<h3>3️⃣ Frontend Setup</h3>

<pre><code>cd ../Frontend
npm install
npm run dev</code></pre>

<hr>

<h2>🌐 Vercel Deployment</h2>

<ol>
  <li>Push your project to GitHub.</li>
  <li>Import it into Vercel.</li>
  <li><b>Framework Preset:</b> Other</li>
  <li><b>Build Command:</b> npm run build</li>
  <li><b>Output Directory:</b> Frontend/dist</li>
</ol>

<h3>Environment Variables</h3>
<ul>
  <li>MONGO_URI</li>
  <li>RAZORPAY_KEY_ID</li>
  <li>RAZORPAY_KEY_SECRET</li>
  <li>EMAIL_ADDRESS</li>
  <li>EMAIL_PASSWORD</li>
  <li>VERCEL=true</li>
</ul>

<p><b>Note:</b> For automatic overdue notices, configure Vercel Cron Jobs to ping:
<code>/api/overdue-books</code></p>

<hr>

<h2>🔗 Live Links</h2>

<p>
🌍 <b>Live Deployment:</b> 
<a href="https://nexus-p1.vercel.app/" target="_blank">
https://nexus-p1.vercel.app/
</a>
</p>

<p>
📱 <b>Android APK:</b> 
<a href="https://drive.google.com/file/d/1t7QJjU9M83p6iYZgev2vf_CHcU5jNOJi/view?usp=drivesdk" target="_blank">
Download APK
</a>
</p>

<hr>

<h2>👨‍💻 Technical Contributors</h2>

<ul>
  <li><b>Anshuman Barik</b> – Backend Developer</li>
  <li><b>Piyush Tiwari</b> – Backend Developer</li>
  <li><b>Siddhant Jena</b> – Frontend Developer</li>
</ul>

<hr>

<h2>📄 License</h2>

<p>
This project is developed for Siksha 'O' Anusandhan. All rights reserved.
</p>

<p align="center">
Developed with ❤️ by <b>Nexus-E4</b>
</p>
