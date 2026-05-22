# Exno.7 - Develop a prompt-based application tailored to their personal needs, fostering creativity and practical problem-solving skills while leveraging the capabilities of large language models.

**Date:** 22/05/2026

**Register No:** 212223040103

---

## Aim

To develop a prompt-based application using ChatGPT - To demonstrate how to create a prompt-based application to generate personalized workout routines, showing the progression from simple to more advanced prompt designs and their corresponding outputs.

---

## AI Tools Required

ChatGPT, Antigravity

---

## Explanation

**Prompt:** Create a modern responsive web application called “AI Workout Routine Generator”.

Purpose:
The app should help users generate personalized workout plans using prompt-based AI interaction.

Features Required:
1. A clean homepage with the title “Workout Routine Generator”.
2. Input form fields for:
   - Fitness Goal (Weight Loss, Muscle Gain, Fitness, Strength)
   - Workout Experience (Beginner, Intermediate, Advanced)
   - Available Time Per Day
   - Available Equipment
   - Number of Workout Days Per Week
3. A “Generate Workout Plan” button.
4. After submission, generate a detailed workout routine using AI-style responses.
5. Display:
   - Daily workout schedule
   - Exercises
   - Sets and repetitions
   - Rest time
   - Tips and motivation
6. Add attractive UI with cards, gradients, and responsive design.
7. Include dark/light mode toggle.
8. Add loading animation while generating the plan.
9. Use modern fonts and smooth animations.
10. Make the design minimalistic and professional.

Technical Requirements:
- Use React and Tailwind CSS.
- Mobile-friendly responsive layout.
- Organize code cleanly into components.
- Add placeholder AI-generated responses if API is not connected.
- Include comments explaining major sections.

Extra Features:
- Add a BMI calculator section.
- Add downloadable workout summary.
- Add motivational quote of the day.

---

### App Requirements

**Core Features:**
- Select fitness goal (Weight Loss, Muscle Gain, General Fitness, Strength)
- Choose workout experience level (Beginner, Intermediate, Advanced)
- Set available time per day (30, 45, 60, or 90 minutes)
- Select available equipment (Bodyweight, Dumbbells, Kettlebells, Resistance Bands, Full Gym)
- Choose number of workout days per week (2–6 days)
- Generate a detailed daily workout schedule with exercises, sets, repetitions, rest time, tips, and motivation
- BMI Calculator with metric and imperial support
- Downloadable workout summary as a text file
- Motivational quote of the day

---

### Tech Stack

- **Frontend:** React (with Tailwind CSS for styling)
- **Build Tool:** Vite
- **Icons:** Lucide React
- **Fonts:** Google Fonts (Plus Jakarta Sans, Inter)
- **State Management:** React Hooks (useState, useEffect)

---

### Frontend Requirements

- Navbar with brand logo and dark/light mode toggle
- Form with custom interactive card selectors for goal, experience, time, equipment, and days per week
- Simulated AI loading console with step-by-step compilation messages
- Tabbed workout plan display:
  - Daily workout schedule with exercises, sets, reps, and rest
  - Warm-up and cool-down routines
  - Coach tips and nutrition recommendations
- BMI calculator with a color-coded classification gauge
- Motivational quote of the day card
- Download and copy-to-clipboard actions for the generated plan

---

### Backend Requirements

No dedicated backend is required. The application is fully client-side. The workout generation logic is handled by a custom utility (`workoutGenerator.js`) that procedurally constructs personalized plans based on the selected parameters.

If extended to a full-stack setup, RESTful API endpoints could include:

- `POST /plans` → Save a generated workout plan
- `GET /plans` → Retrieve all saved plans
- `GET /summary` → Get aggregated workout statistics
- `DELETE /plans/:id` → Delete a saved plan

---

### Bonus Features (Implemented)

- Dark mode toggle with localStorage persistence
- BMI Calculator supporting both Metric (kg/cm) and Imperial (lbs/ft-in) units
- Downloadable workout summary as a formatted `.txt` file
- Copy plan to clipboard
- Motivational quote of the day

---

### UI/UX Design Goals

- Clean and minimal layout with glassmorphism-styled cards
- Soft shadows, rounded corners, and modern typography
- Smooth micro-animations and hover effects
- Mobile-friendly and fully responsive across all screen sizes
- Premium color palette with gradient accents

---

### Functional Flow

- User opens the app → sees the hero header and configuration form
- User selects fitness goal, experience level, time, equipment, and workout days
- User clicks "Generate AI Workout Plan" → a simulated CLI console appears, printing compilation steps
- After the animation, a detailed workout plan is displayed
- User browses daily workouts, warm-up/cool-down, tips, and nutrition using tabs
- User downloads or copies the full plan
- User scrolls down to the BMI Calculator → enters height and weight → receives classification and advice
- Motivational quote of the day is displayed at the bottom of the page

---

### Expected Output

Generate full code (frontend), including:
- React components for Navbar, WorkoutForm, WorkoutPlanDisplay, BMICalculator, and QuoteOfTheDay
- Utility module (`workoutGenerator.js`) with a full exercise database and plan logic
- Tailwind CSS configuration with custom animations
- Instructions on how to run the app locally
- Optional: Suggest deployment steps on Vercel / Netlify

---

### Home Page 
<img width="1919" height="1079" alt="Screenshot 2026-05-22 134613" src="https://github.com/user-attachments/assets/4fbfe98f-c14f-4980-936d-58d6c8b78716" />
<img width="1919" height="967" alt="Screenshot 2026-05-22 134628" src="https://github.com/user-attachments/assets/ef40c2f6-437e-4f56-b7f8-7f8f029437ea" />
<img width="1914" height="844" alt="Screenshot 2026-05-22 134707" src="https://github.com/user-attachments/assets/255677f3-c8f7-4900-9f7e-adc2e603eed6" />


### Generated Workout Plan:

<img width="1919" height="970" alt="Screenshot 2026-05-22 135017" src="https://github.com/user-attachments/assets/4fa5d22c-3615-48b3-9633-d57534d9ee28" />

---

## Result

A fully functional, AI-generated Workout Routine Generator Web Application was successfully developed using prompt-based design with ChatGPT. The application allows users to:

→ Select their fitness goal, experience level, time, equipment, and workout frequency.  
→ Generate a detailed, personalized workout routine with exercises, sets, reps, and rest times.  
→ View warm-up and cool-down routines along with coaching tips and nutrition advice.  
→ Calculate their BMI with instant categorization and actionable feedback.  
→ Download or copy the complete workout plan for offline use.

This demonstrates the power of prompt engineering in developing complete, production-ready web applications efficiently.
