# Nutrition-Advisor-AI-Agent

# 🥗 Personalized Nutrition Advisor  

This repository implements an **AI-powered Personalized Nutrition Advisor** that provides customized diet and nutrition plans based on user inputs such as demographics, health conditions, and dietary preferences.  

## 🚀 Features  

- **AI-Powered Nutrition Agents** - Specialized agents for nutrition research, medical analysis, and diet planning  
- **Automated Dietary Recommendations** - Generates meal plans based on scientific principles  
- **Medical-Nutrition Integration** - Adjusts meal plans based on medical conditions and medications  
- **Interactive User Input via Streamlit** - Collects user details and preferences for personalized recommendations  
- **LLM-Powered Intelligence** - Utilizes OpenAI’s `o1-mini` model for generating responses  
- **Real-Time Web Search** - Integrates `SerperDevTool` for retrieving latest nutrition research  

## 🔧 Implementation Details  

### **Agent-Based AI Model**  

The system leverages **CrewAI** to create intelligent agents specialized in different aspects of nutrition:  

1. **Nutrition Specialist** - Researches and recommends nutritional needs  
2. **Medical Nutrition Therapist** - Adjusts diet plans based on medical conditions  
3. **Therapeutic Diet Planner** - Creates meal plans, shopping lists, and recipes  

These agents work together in a structured pipeline to deliver comprehensive recommendations.  

### **User Information Collection**  

The system gathers the following details:  

- **Personal Information**: Age, gender, height, weight, activity level, nutrition goals  
- **Health Details**: Medical conditions, medications, food allergies  
- **Dietary Preferences**: Food likes/dislikes, cooking skills, budget constraints, cultural/religious factors  

### **AI-Powered Nutrition Plan Generation**  

- **Nutritional Research**: Calculates caloric intake, macronutrients, micronutrients  
- **Medical Analysis**: Adjusts diet for medical conditions and food-medication interactions  
- **Meal Planning**: Generates a **7-day meal plan**, shopping list, and meal preparation tips  

## 📊 Example Usage  

```python
# Run the Streamlit app
if __name__ == "__main__":
    app()
```

## 🛠️ Setup and Requirements  

This project requires the following dependencies:  

```bash
pip install streamlit crewai langchain_openai dotenv faiss-gpu
```

### **Environment Variables**  
Create a `.env` file and add your API keys:  

```ini
SERPER_API_KEY=your_serper_api_key
OPENAI_API_KEY=your_openai_api_key
```

## 🎯 Applications  

- AI-powered **personalized diet planning**  
- **Medical-nutrition integration** for condition-specific dietary recommendations  
- **Meal planning automation** with AI-driven food recommendations  
- **Dynamic food recommendations** based on real-time search and LLM integration  

## 🔍 Future Improvements  

- Enhance **meal customization** for more diverse preferences  
- Implement **goal-based adaptive planning** for weight management  
- Integrate **visual meal recommendations** with nutritional breakdowns  
- Improve **model fine-tuning** for better dietary predictions  
