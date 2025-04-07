# My Projects

Welcome to my projects page! Here you'll find more detailed information about the various software, hardware, and research projects I've worked on.

---

## Table of Contents

- [My Projects](#my-projects)
  - [Table of Contents](#table-of-contents)
  - [NewLedger](#newledger)
  - [Flashy](#flashy)
  - [ListVaults](#listvaults)
  - [PlanMyTrip](#planmytrip)
  - [Personal Landing Page](#personal-landing-page)
  - [Hosted Static Website on Amazon S3](#hosted-static-website-on-amazon-s3)
  - [Arduino Joystick Control Car](#arduino-joystick-control-car)
  - [Rube-Goldberg Machine](#rube-goldberg-machine)
  - [Video Game Design Workshop Project](#video-game-design-workshop-project)

---

## NewLedger

_(Flutter, Dart, Firebase, Hive, Google ML Kit, Swift [initial phase]) | Dec 2024 - Present_

**Description:** A cross-platform personal finance management application designed to simplify expense tracking, budgeting, and collaborative cost-splitting.

**Motivation:** Inspired by the difficulty of tracking expenses during a trip, I wanted an app to easily log costs, categorize them, and see summaries, especially for shared expenses.

**Key Features & Contributions:**

- **Technical Implementation:**
  - Engineered using Flutter for cross-platform compatibility (iOS & Android) after initially exploring Swift.
  - Utilized Firebase (Firestore/Realtime Database) and Hive (for local persistence) to create a scalable database architecture.
  - Implemented secure user authentication via Firebase Authentication.
  - Integrated Google ML Kit for receipt scanning, developing custom OCR algorithms to automate expense entry and reduce manual input time by approximately 70%.
- **Feature Development:**
  - Developed an intuitive expense splitting system with real-time updates for efficient cost sharing among friends/groups.
  - Created a comprehensive financial analytics dashboard using Material Design principles, featuring interactive charts and customizable reports for detailed spending insights.
  - Implemented multi-currency support by integrating exchange rate APIs for automated conversion, allowing seamless tracking across different currencies.
- **User Experience:**
  - Designed and implemented dark/light theme functionality using Provider for state management, offering customizable interface options.
  - Built an advanced filtering and search system for efficient expense categorization and analysis.
  - Incorporated robust data visualization using custom Flutter widgets.

**Challenges:** Transitioning from Swift (with its readily available UI libraries) to Flutter/Dart required building more UI components from scratch. Learning local data storage with Hive alongside Firebase was also a key learning experience. Leveraged ClaudeAI extensively for debugging, syntax understanding, and learning best practices.

---

## Flashy

_(NextJS, JavaScript, Firebase, GroqAI, Clerk, Material UI) | August 2024 (Headstarter Fellowship Project - 60 hours)_

**Description:** An AI-powered flashcard creation platform designed to enhance learning and memory retention.

**Key Features & Contributions:**

- Generates up to 12 detailed flashcards per session using GroqAI, focusing on thought-provoking questions and comprehensive answers with examples.
- Built a secure and scalable backend using Firebase, allowing users to create, save, and edit unlimited flashcards.
- Integrated Clerk authentication to safeguard user data for 10+ active users with zero data breaches.
- Optimized the user experience with a highly intuitive interface (Material UI), resulting in a measured 40% increase in user retention.
- Empowers users to customize flashcards for personalized learning.

**Link:** [https://flashyai.vercel.app/](https://flashyai.vercel.app/)

---

## ListVaults

_(NextJS, JavaScript, Firebase) | August 2024 (Headstarter Fellowship Project - 40 hours)_

**Description:** A comprehensive website for managing and tracking various media watch lists, particularly focused on anime and drama.

**Key Features & Contributions:**

- Deployed on Vercel, attracting 20+ users.
- Enabled the creation of different list types on a single platform with dedicated "to-watch" and "watched" sections, improving user organization by 30%.
- Implemented seamless item movement between "to-watch" and "watched" states upon completion, increasing user engagement by 14%.
- Provided functionality for users to edit list items, enhancing customization and increasing user satisfaction by 20%.

**Link:** [https://listvaults.vercel.app/](https://listvaults.vercel.app/)

---

## PlanMyTrip

_(Groq AI, ReactJS, NextJS, Material UI) | August 2024 (Headstarter Fellowship Project - 40 hours)_

**Description:** An AI-powered platform designed to simplify and enhance the travel planning experience.

**Key Features & Contributions:**

- Developed an interactive interface offering tailored travel recommendations and personalized itinerary mapping using Groq AI.
- Integrated helpful tools like packing checklists, essential travel tips, and timely reminders for crucial tasks (booking, transport, documents).
- Streamlined complex logistics, allowing users (solo or groups) to focus on enjoying their trip.
- Adapted the platform to cater to unique user preferences and varied travel styles.

**Link:** [https://plan-my-trip-ai.vercel.app/](https://plan-my-trip-ai.vercel.app/)

---

## Personal Landing Page

_(HTML, CSS, DNS, Google Analytics) | July 2024_

**Description:** A central, static web page serving as a portfolio to showcase my various projects.

**Key Features & Contributions:**

- Created using fundamental web technologies (HTML, CSS).
- Configured DNS settings for a custom domain (likely hosted via GitHub Pages based on URL structure).
- Integrated Google Analytics for tracking visitor metrics.

**Link:** [https://yanglin14.github.io/personal-website/](https://yanglin14.github.io/personal-website/)

---

## Hosted Static Website on Amazon S3

_(AWS S3, AWS Route 53, HTML) | July 2024 (Self-Learning Project)_

**Description:** A self-directed project to learn cloud hosting basics by deploying a static website using AWS services.

**Key Features & Contributions:**

- Created and configured an S3 bucket for static website hosting.
- Uploaded HTML and image files, enabling public access.
- Implemented an S3 bucket policy to prevent accidental file deletion and enable versioning for recovery.
- Purchased and configured a domain using Route 53 to point to the S3 website endpoint.
- Utilized pre-signed URLs for temporary, secure sharing of specific objects within the bucket.

---

## Arduino Joystick Control Car

_(Arduino, C++, 3D Printing (Fusion360), Electronics) | January 2023 - April 2023 (IEEE Club Vice President Role @ Ohlone College)_

**Description:** Led a team within the Ohlone College IEEE club to design, build, and program a joystick-controlled race car.

**Key Features & Contributions:**

- Served as Vice President, overseeing the project and team members.
- Designed and 3D printed a custom race car chassis incorporating light sensors, a microprocessor, and an Arduino board.
- Wrote C++ code to implement the car's logic and control system.
- Taught team members essential skills: 3D printing, 3D modeling (Fusion360), wiring, soldering, and hardware/software integration.
- Guided the team in establishing wireless communication between the joystick controller and the car's receiver.
- Managed task assignments and facilitated team meetings to address challenges and track progress within a limited timeframe.
- Successfully showcased the autonomous/controlled car at Ohlone College's Club Rush and Career Fair.

**Challenges:** Managing task delegation and teaching a large group effectively within project constraints. Implemented a structured approach with team leads and segmented tasks to overcome this.

---

## Rube-Goldberg Machine

_(Arduino, Sensors, Microcontrollers) | August 2021 (Workshop @ Cal Poly San Luis Obispo)_

**Description:** Designed and built multiple iterations of a Rube-Goldberg machine as part of a workshop experience.

**Key Features & Contributions:**

- Designed 6 distinct versions of the machine, experimenting with different sensors and microcontrollers (primarily Arduino).
- Iteratively refined the design based on testing and workshop goals.
- The finalized design successfully operated complex sequences triggered by a single push-button interface.

---

## Video Game Design Workshop Project

_(Unity3D, C#) | June 2021 - July 2021 (Workshop @ Cal Poly Pomona)_

**Description:** Developed a functional video game during an intensive game design, development, and production workshop.

**Key Features & Contributions:**

- Created a zombie shooting game using the Unity3D engine.
- Implemented game logic and AI algorithms for enemy behavior using C#.
- Designed the game with 3 distinct stages of increasing difficulty.
- Implemented core player mechanics, including both first-person and third-person perspectives, and the ability to switch between weapons.

---

[Back to Main Page](./index.md)
