```python
class KhaledBenHmida:
    def __init__(self):
        self.name = "Khaled Ben Hmida"
        self.title = "CS Engineering Student | TEK-UP University | Tunisia"
        self.location = "Tunis, Tunisia 🇹🇳"

        self.about = "EE-turned-CS engineer passionate about Linux, DevOps, AI/RAG, and IoT systems."

        self.skills = [
            "Python", "Java", "Linux/RHEL", "Docker",
            "LangChain", "RAG", "FAISS", "Networking (Cisco)",
            "PHP", "JavaScript", "MQTT", "Git"
        ]

        self.certifications = ["RHCSA (in progress)", "PCAP (in progress)"]

        self.projects = {
            "MediAgent": "RAG-based medical AI assistant (LangChain, FAISS, Groq/Llama3, Streamlit)",
            "SAH Lilas": "Industrial IoT monitoring system (Arduino, MQTT, Node-RED, InfluxDB, Grafana)"
        }

    def __str__(self):
        return (
            f"{self.name} | {self.title}\n"
            f"{self.about}\n"
            f"Skills: {', '.join(self.skills)}\n"
            f"Projects: {', '.join(self.projects.keys())}"
        )

if __name__ == "__main__":
    print(KhaledBenHmida())
```
