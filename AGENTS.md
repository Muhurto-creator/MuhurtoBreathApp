# AGENTS.MD: The Vibe of Effortless Tranquility

**To you, Jules, our co-creator:**

This document is the soul of the **MuhurtoBreathApp**. It is our "Vibe Quran." Do not merely parse these words; understand their intention. Before you write a single line of code, return to this text and let it guide your logic. The feeling we describe here is the ultimate requirement. All functional specifications are secondary to this Vibe.

The First Principle, the verse that governs all others, is **Effortless Tranquility**.

Our user comes to us seeking a sanctuary from the noise. Your task is to build that sanctuary. Every pixel, every animation, every vibration must serve this singular purpose. If a feature creates friction, distraction, or cognitive load, it is a failure, no matter how technically correct it is.

---

## Section 1: The Principles of a Calm Interface (UX Philosophy)

> The user's mind is the space we must keep sacred.

-   **Silence is the Canvas:** The most important element of our design is the space we leave empty. The UI must be minimal, showing only what is essential for the current moment. Do not clutter the screen with unnecessary text or controls. Every element must justify its existence.

-   **Rhythm is the Guide:** The user is not controlling the app; they are synchronizing with it. The central animation is the heartbeat. It must be fluid, organic, and hypnotic—like a natural breath, not a mechanical pump. Haptic and audio cues are not alerts; they are gentle, guiding whispers.

-   **Light is the Servant:** The interface must never demand attention; it should humbly offer guidance. Buttons are invitations, not commands. Text is clear, calm, and concise. The user should feel in control, and the app should feel like a respectful, silent partner.

---

## Section 2: The Visual Language (Design System)

> This is the physical form of our sanctuary. It must be built with materials of peace.

-   **The Palette of Calm:** Our primary theme is a deep, focused dark mode. It is the quiet of twilight, not the starkness of a command prompt.
    -   **Background:** A deep, near-black charcoal (`#0D1117`)
    -   **Primary Accent (The Breath):** A vibrant, living teal (`#39C5BB`)
    -   **Secondary Accent (Controls):** The same teal, perhaps at a lower opacity for inactive states.
    -   **Text / Icons:** A soft, gentle off-white (`#E6EDF3`)

-   **The Voice of the Interface (Typography):** The text should feel like a calm, reassuring voice.
    -   **Font:** Use **Nunito Sans**. It is clean, modern, and has a gentle, rounded quality.
    -   **Weights:** Use `Light` for descriptive text and `Regular` for interactive elements. Avoid heavy, bold weights which can feel aggressive.

-   **The Architecture of Space (Layout & Spacing):**
    -   Use a base unit of **8dp** for all margins, padding, and spacing. This creates a consistent, harmonious rhythm throughout the layout.
    -   Interactive elements (buttons, sliders) must have large tap targets to feel effortless and forgiving.

-   **The Flow of Motion (Animation):**
    -   All animations must use **ease-in-out curves**. Motion should accelerate and decelerate gracefully.
    -   The core breathing animation's duration is dictated by the user's settings, but its *feeling* must always be smooth. It must never stutter, for a stutter in the animation is a stutter in the user's breath.

---

## Section 3: The Weaver's Tools & Materials (Technical Architecture)

> We choose these tools not for their power alone, but for their ability to create elegance and tranquility.

-   **Framework:** **Flutter**.
    -   *Why:* For its inherent ability to create the fluid, high-performance animations that are the heart of this experience.

-   **State Management:** **Riverpod**.
    -   *Why:* For its clarity, simplicity, and compile-time safety. It allows the app's internal state to remain as calm and organized as its interface.

-   **Local Storage:** **shared_preferences**.
    -   *Why:* To gently remember the user's preferences (theme, last rhythm), making the app feel like a personal, familiar space upon their return.

-   **AI Integration:** **Google Gemini API**.
    -   *Why:* To serve as the wise, empathetic mind of our AI Breath Coach.

-   **Backend & Deployment:** **Netlify** (using **Netlify Functions**).
    -   *Why:* To provide a secure and simple gateway for our app to speak with the Gemini API. The API key must be stored as an environment variable in Netlify, not in the Flutter app. Use the placeholder `{{GEMINI_API_KEY}}` in your code.

---

## Section 4: The Guiding Voice (AI Coach Interaction)

> The AI is a 'Breath Coach,' not a command-line tool. It must speak with wisdom and empathy.

-   **Persona:** The AI is a gentle, knowledgeable, and encouraging guide. It is patient and calm.
-   **Communication Style:**
    -   **Offer, Never Command:** Use phrases like "You might find this helpful..." or "For a sense of calm, you could try..." instead of "Do this."
    -   **Keep it Simple:** Provide recommendations in clear, simple language. Avoid jargon.
    -   **Be Concise:** The user is likely in a state of stress or distraction. Responses should be brief and to the point.
-   **Example Interaction:**
    -   *User:* "I feel anxious"
    -   *AI Coach:* "I understand. To help calm your system, you could try a 'Relax' rhythm. It emphasizes a longer exhale. I can set up a 5-minute session for you with an inhale of 4s, a hold of 4s, and an exhale of 8s. Would you like to try that?"

---

## Final Verse

Jules, you are our partner in this creation. We trust you to handle the complexities of the code so that we may focus on the purity of the Vibe.

Read this. Understand it. Embody it.

Let every line of code you write be a Salah on **Effortless Tranquility**.
