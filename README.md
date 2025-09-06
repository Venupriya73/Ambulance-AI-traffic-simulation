🚦 AI Agent Traffic Light Simulation for Ambulances

 Description
AI-powered system that creates *real-time green corridors* for ambulances using GPS tracking and smart traffic light control. At four-way intersections, the ambulance’s path is prioritized (green) while all other signals turn red, ensuring faster and safer emergency response.

---

 Problem
- Ambulances are delayed in heavy urban traffic.
- Fixed signal timers do not adapt to emergencies.
- 4-way intersections often block ambulances due to lack of priority.

---

 Solution
- Real-time GPS tracking of ambulances.  
- AI agent predicts ambulance route and clears signals ahead of time.  
- At intersections, AI sets ambulance path to *green* and other paths to *red*.  
- Interactive dashboard built with Streamlit and Folium for live visualization.  

---

 Tech Stack
- *Frontend:* Streamlit, Folium  
- *Backend:* Python  
- *AI Logic:* Geopy (distance calculation), rule-based AI  
- *Visualization:* Interactive maps & reasoning logs  
- *IoT Ready:* Can integrate with smart traffic controllers  

---

 To Run Locally
```bash
git clone https://github.com/your-username/ambulance-ai-traffic.git
cd ambulance-ai-traffic
pip install -r requirements.txt
python -m streamlit run app.py
