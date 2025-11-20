import { FaGithub, FaLinkedin } from "react-icons/fa";
import { FaLayerGroup } from "react-icons/fa6";
import { FaInstagram } from "react-icons/fa";

export default function PortfolioSection() {
  return (
    <div className="min-h-screen bg-gray-900 text-white px-6 py-12">

      {/* Heading */}
      <h1 className="text-4xl font-bold mb-4">
        👋 Hi there, I'm <span className="text-blue-400">Vinay Karad</span>
      </h1>

      <p className="text-lg text-gray-300 mb-6">
        🎓 <b>Computer Engineering Student</b>  
        <br />
        💻 Passionate about <b>Java</b>, <b>Web Development</b>, <b>C++</b>, and <b>DSA</b>  
        <br />
        🤖 Currently building an <b>AI-powered Healthcare Chatbot</b>
      </p>

      <hr className="border-gray-700 my-6" />

      {/* About Me */}
      <h2 className="text-2xl font-semibold mb-3">🚀 About Me</h2>

      <p className="text-gray-300 mb-4">
        I am a Computer Engineering student with strong knowledge in programming,
        software development, and problem-solving. I have experience in Machine
        Learning and Web Development. I am a quick learner with good teamwork and 
        communication skills.
      </p>

      <ul className="text-gray-300 space-y-2 mb-6">
        <li>🌱 <b>Currently Learning</b>: Data Structures & Algorithms, Cloud Computing</li>
        <li>🎯 <b>Goal</b>: Seeking exciting internship and job opportunities</li>
        <li>
          🛠️ <b>Skills</b>:
          <code className="ml-2 bg-gray-800 px-2 py-1 rounded">Java</code>{" "}
          <code className="bg-gray-800 px-2 py-1 rounded">C++</code>{" "}
          <code className="bg-gray-800 px-2 py-1 rounded">Web Development</code>{" "}
          <code className="bg-gray-800 px-2 py-1 rounded">HTML/CSS/JS</code>{" "}
          <code className="bg-gray-800 px-2 py-1 rounded">DSA</code>
        </li>
      </ul>

      <hr className="border-gray-700 my-6" />

      {/* Projects */}
      <h2 className="text-2xl font-semibold mb-3">💼 Projects</h2>

      <h3 className="text-xl font-semibold text-blue-400">
        🔹 AI-Powered Healthcare Chatbot
      </h3>
      <p className="text-gray-300 mb-4">
        Built a voice-enabled chatbot supporting Hindi, English, and Marathi.
        Integrated speech recognition, TTS, and Akash decentralized cloud for secure health data.
      </p>

      <h3 className="text-xl font-semibold text-blue-400">
        🔹 Healthcare Waste Management System
      </h3>
      <p className="text-gray-300 mb-6">
        Developed a web platform to track biomedical waste disposal with real-time digital records.
      </p>

      <hr className="border-gray-700 my-6" />

      {/* Contact Me */}
      <h2 className="text-2xl font-semibold mb-4">📫 Contact Me</h2>

      {/* BUTTONS */}
      <div className="flex gap-4 mb-10">

        {/* LinkedIn */}
        <a
          href="https://www.linkedin.com/in/vinay-karad-8b5b77344/"
          target="_blank"
          className="flex items-center gap-2 bg-blue-600 px-6 py-3 rounded-md 
                     text-white font-semibold tracking-widest hover:bg-blue-700 transition"
        >
          <FaLinkedin className="text-xl" />
          LINKEDIN
        </a>

        {/* Portfolio */}
        <a
          href="https://vinaykarad.com"
          target="_blank"
          className="flex items-center gap-2 bg-orange-500 px-6 py-3 rounded-md 
                     text-white font-semibold tracking-widest hover:bg-orange-600 transition"
        >
          <FaLayerGroup className="text-xl" />
          PORTFOLIO
        </a>

        {/* GitHub */}
        <a
          href="https://github.com/vinaykarad"
          target="_blank"
          className="flex items-center gap-2 bg-purple-600 px-6 py-3 rounded-md 
                     text-white font-semibold tracking-widest hover:bg-purple-700 transition"
        >
          <FaGithub className="text-xl" />
          GITHUB
        </a>

      </div>

      {/* Round Social Icons */}
      <div className="flex gap-6 items-center">

        <a
          href="https://github.com/vinaykarad"
          target="_blank"
          className="w-16 h-16 rounded-full bg-purple-500 flex items-center justify-center 
                     text-white text-3xl hover:scale-110 transition transform"
        >
          <FaGithub />
        </a>

        <a
          href="https://www.linkedin.com/in/vinay-karad-8b5b77344/"
          target="_blank"
          className="w-16 h-16 rounded-full bg-blue-600 flex items-center justify-center 
                     text-white text-3xl hover:scale-110 transition transform"
        >
          <FaLinkedin />
        </a>

        <a
          href="https://instagram.com"
          target="_blank"
          className="w-16 h-16 rounded-full bg-pink-500 flex items-center justify-center 
                     text-white text-3xl hover:scale-110 transition transform"
        >
          <FaInstagram />
        </a>

      </div>

    </div>
  );
}

