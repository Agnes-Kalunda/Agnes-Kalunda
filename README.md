#!/usr/bin/python
# -*- coding: utf-8 -*-

class SoftwareEngineer:
    def __init__(self):
        self.name = "Agnes"
        self.role = "Full Stack Developer"
        self.location = "Nairobi, Kenya"
        self.languages_spoken = ["Swahili", "English"]
        self.status = "Self-taught developer passionate about AI and microservices"

    def say_hi(self):
        print("Hi! Thanks for dropping by.")
        print("Hope you find some of my work interesting!")

    def get_tech_stack(self):
        return {
            "frontend": ["JavaScript", "TypeScript", "React.js", "Vue.js", "HTML5", "CSS3"],
            "backend": ["Python", "Django", "FastAPI", "PHP", "Laravel", "Node.js"],
            "databases": ["PostgreSQL", "MySQL"],
            "cloud_devops": ["AWS", "Docker", "EC2", "GitHub Actions", "CI/CD"],
            "ai_ml": ["TensorFlow", "PyTorch", "OpenAI API", "Hugging Face", "Langchain"],
            "tools": ["Git", "VS Code", "Postman", "Docker Compose"]
        }

    def current_journey(self):
        return {
            "learning": ["Microservices Architecture", "Kubernetes"],
            "ai_interests": ["LLMs", "RAG Systems", "AI-powered Applications", "Chatbots"],
            "building": ["AI-integrated web apps", "Microservice APIs", "SaaS solutions"],
            "self_teaching": "Constantly expanding knowledge through projects and practice"
        }

    def display_profile(self):
        print(f"{self.name} | {self.role}")
        print(f"{self.location} |  {', '.join(self.languages_spoken)}")
        print(f"{self.status}")
        
        print("Tech Stack:")
        for category, techs in self.get_tech_stack().items():
            print(f"  • {category.replace('_', ' ').title()}: {', '.join(techs)}")
        
        print("Current Journey:")
        for key, value in self.current_journey().items():
            if isinstance(value, list):
                print(f"  {key}: {', '.join(value)}")
            else:
                print(f"  {key}: {value}")
        
        print("Let's Connect:")
        print("  • Email: agypeter97@gmail.com")
        
        
        print("Fun Fact: Debugging with ☕ and 🎵, always curious about the next tech trend!")
        print(" Open to collaborations and learning opportunities!")


# Initialize and run
if __name__ == "__main__":
    agnes = SoftwareEngineer()
    agnes.say_hi()
    agnes.display_profile()
    
    print("AI + Code = Endless Possibilities!")
