# CODE
```
import Image from 'next/image';
import Head from 'next/head';

export default function Home() {
  return (
    <>
      <Head>
        <title>Elvi Rose Joshi | Portfolio</title>
      </Head>

      <main className="bg-pink-50 text-black min-h-screen px-6 py-10 font-sans max-w-5xl mx-auto">

        {/* Profile Header */}
        <section className="flex flex-col md:flex-row items-center gap-6 mb-16">
          <div className="relative w-40 h-40 rounded-full overflow-hidden border-4 border-pink-500">
            <Image src="/img.jpg" alt="Elvi Rose Joshi" layout="fill" objectFit="cover" />
          </div>
          <div className="text-center md:text-left">
            <h1 className="text-4xl font-bold text-pink-700 mb-1">Elvi Rose Joshi</h1>
            <p className="text-lg">CSE Student | Passionate about New Trends in Tech</p>
          </div>
        </section>

        {/* About Section */}
        <section className="mb-16 border border-gray-200 bg-white rounded-xl p-6 shadow-sm">
          <h2 className="text-2xl font-semibold text-pink-600 mb-4 text-center">ABOUT</h2>
          <div className="space-y-4 text-justify">
            <p>
              I’m a creative-minded computer science enthusiast who enjoys solving real-world problems through technology. My journey in CSE has fueled my passion for software development, data analytics, and intelligent systems. I believe that data tells powerful stories—and I love diving into datasets to uncover patterns, generate insights, and drive smarter decisions.
            </p>
            <p>
              Whether it’s building user-friendly applications, visualizing data trends, or experimenting with AI models, I strive to bring both logic and creativity to the table. I enjoy working on projects that challenge my thinking and allow me to explore new tools and technologies.
            </p>
            <p>
              Beyond the screen, I’m a strong believer in continuous learning and collaboration. I find inspiration in simplicity, innovation, and the impact that thoughtful design can have on people’s lives.
            </p>
          </div>
        </section>

        {/* Education Section */}
        <section className="mb-16 border border-gray-200 bg-white rounded-xl p-6 shadow-sm">
          <h2 className="text-2xl font-semibold text-pink-600 mb-4 text-center">EDUCATION</h2>
          <ul className="space-y-4">
            <li>
              <strong>Bachelor of Technology (B.Tech) in Computer Science and Engineering</strong><br />
              Viswajyothi College of Engineering & Technology, Ernakulam<br />
              Year: 2022–26
            </li>
            <li>
              <strong>Higher Secondary Education (Class 12)</strong><br />
              Carmel CMI Public School, Ernakulam<br />
              Board: CBSE, Year: 2022
            </li>
            <li>
              <strong>Secondary Education (Class 10)</strong><br />
              Carmel CMI Public School, Ernakulam<br />
              Board: CBSE, Year: 2020
            </li>
          </ul>
        </section>

        {/* Internships Section */}
        <section className="mb-16 border border-gray-200 bg-white rounded-xl p-6 shadow-sm">
          <h2 className="text-2xl font-semibold text-pink-600 mb-4 text-center">INTERNSHIP</h2>
          <ul className="space-y-4">
            <li>
              <strong>Intern at INTERPE</strong><br />
              Domain: AI/ML<br />
              Duration: 23 June – 20 July 2025
            </li>
            <li>
              <strong>Intern at RedTeam Hacker Academy</strong><br />
              Domain: Cybersecurity<br />
              Date: 2 Dec 2023
            </li>
            <li>
              <strong>Intern at QNAYDS</strong><br />
              Domain: Data Science<br />
              Duration: 7 March – 11 March 2023
            </li>
          </ul>
        </section>

        {/* Project Section */}
        <section className="mb-16 flex flex-col md:flex-row gap-6 border border-gray-200 bg-white rounded-xl p-6 shadow-sm">
          <div className="flex-1">
            <h2 className="text-2xl font-semibold text-pink-600 mb-4 text-center">PROJECT</h2>
            <h3 className="text-xl font-bold">ENERGEON: Household Electricity Usage Estimator and Optimizer</h3>
            <p className="mt-2 text-justify">
              The household electricity usage estimator and optimizer aim to empower users to efficiently manage and reduce their electricity consumption by providing accurate bill estimations and actionable optimization suggestions. By analysing user-provided inputs such as daily device usage patterns, the system calculates the estimated electricity bill, identifies areas of excessive consumption and offers recommendations for meeting budgetary targets. This approach promotes energy efficiency, cost saving and sustainable living by combining data visualization, interactive tools and notification systems for an ideal user experience.
            </p>
            <p className="mt-2">
              <strong>Technology Stack</strong><br />
              Frontend: HTML, CSS, JavaScript<br />
              Backend: Node.js, Express<br />
              Database: MongoDB
            </p>
          </div>
        </section>

        {/* Skills Section */}
        <section className="mb-16 border border-gray-200 bg-white rounded-xl p-6 shadow-sm">
          <h2 className="text-2xl font-semibold text-pink-600 mb-4 text-center">SKILLS</h2>
          <div className="flex flex-wrap gap-[2cm]">
            {['Python', 'C', 'Excel', 'MySQL', 'HTML', 'CSS', 'Java'].map(skill => (
              <span key={skill} className="px-4 py-1 bg-orange-100 border border-pink-500 rounded-full text-sm">
                {skill}
              </span>
            ))}
          </div>
        </section>

        {/* Contact Section */}
        <section className="border border-gray-200 bg-white rounded-xl p-6 shadow-sm">
          <h2 className="text-2xl font-semibold text-pink-600 mb-4 text-center">CONTACT</h2>
          <div className="text-left">
            <p>Email: <a href="mailto:elvirose351@gmail.com" className="text-pink-600 underline">elvirose351@gmail.com</a></p>
            <p>LinkedIn: <a href="https://www.linkedin.com/in/elvi-rose-joshi/" target="_blank" className="text-pink-600 underline">linkedin.com/in/elvi-rose-joshi</a></p>
            <p>GitHub: <a href="https://github.com/Elvirose" target="_blank" className="text-pink-600 underline">github.com/Elvirose</a></p>
          </div>
        </section>
      </main>
    </>
  );
}

```
![port](https://github.com/user-attachments/assets/71ab41cd-06c2-4042-b667-b034c3853481)
![image](https://github.com/user-attachments/assets/d9b53f4a-1e4d-49bf-885d-38f8c7e51728)
![image](https://github.com/user-attachments/assets/bfb46b2d-c6ea-4c0f-8a25-c8225f2a020f)

