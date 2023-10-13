# MediSavvy

### Addressing the Medication Maze

In an era where health is paramount, navigating the realm of medication can be likened to a labyrinth. Patients often find themselves lost in the labyrinth of comparing medicine prices across various online platforms, a task that can be incredibly daunting, particularly when multiple prescriptions are involved. This challenge escalates when it comes to high-cost medications, where potential savings can be substantial. From deciphering medication names to procuring them from online pharmacies and staying on top of dosage schedules, the process can be overwhelming. There is an urgent need for a solution that simplifies this journey.

### Introducing MediSavvy

- **MediSavvy** is a revolutionary platform designed to redefine how patients acquire and manage medications, harnessing the power of advanced technologies. Employing state-of-the-art **Optical Character Recognition (OCR)** through **Google Cloud Vision**, we extract precise medication details from prescriptions. The Med7 **machine learning model** integrated with **spaCy** is then utilized to identify medication names, dosages, and frequencies.

- To ensure seamless data retrieval and management, we implement an efficient caching system for extracted medication details and prices within a robust database. The backend, coded in Python, excels in data processing, price comparisons, and medication scheduling, optimized through multi-threading for peak performance. **Web scraping techniques** are employed to fetch real-time medication prices from a myriad of online pharmacies.

- The frontend boasts an elegant **React-based user interface**, presenting medication details including names, dosages, durations, and prices from diverse sources. Additionally, patients have access to an interactive calendar for scheduling medication reminders and tracking dosages. This calendar seamlessly syncs with **Google Calendar**, ensuring patients receive reminders across all their devices and platforms.

- **MediSavvy** is poised to streamline the medication procurement process, unlocking substantial cost-saving opportunities for patients, and providing them with an intuitive platform for managing their medication schedules.