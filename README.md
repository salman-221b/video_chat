# Django Video Chat with Agora SDK

Welcome to the **Django Video Chat** project using the Agora SDK! This project allows users to create and join video chat rooms, providing a seamless video conferencing experience. Users can enter a room by providing a unique room name and their own name. They can then share the room name with their friends, allowing them to easily join the video chat. Here is the live demo of this app on [Heroku](https://videofy-88712c3259f4.herokuapp.com)

## Features

- Create and join video chat rooms.
- Real-time video conferencing using Agora SDK.
- Simple and intuitive user interface.
- Shareable room names for easy room access.
- Responsive design for both desktop and mobile devices.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.x installed on your system.
- Django framework installed. You can install it using `pip`:

  ```bash
  pip install django
  ```

## Getting Started

To set up and run the project locally, follow these steps:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/salman-221b/video_chat.git
   ```

2. Navigate to the project directory:

   ```bash
   cd video_chat
   ```

3. Install the project dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Set up your Agora account and obtain an App ID. Replace `'YOUR_AGORA_APP_ID'` in `streams.js` with your actual Agora App ID.

5. Apply migrations to create the necessary database tables:

   ```bash
   python manage.py migrate
   ```

6. Start the development server:

   ```bash
   python manage.py runserver
   ```

7. Open your web browser and go to `http://127.0.0.1:8000` to access the application.

## Usage

1. On the homepage, enter your desired room name and your name.

2. Click the "Join Room" button to enter the video chat room.

3. Share the room name with your friends, so they can enter the same room.

4. To join the room, your friends should navigate to the homepage, enter the same room name, and provide their names.

5. Once everyone has joined, the video chat session will begin.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.

2. Create a new branch for your feature or bug fix:

   ```bash
   git checkout -b feature/your-feature-name
   ```

3. Make your changes and commit them:

   ```bash
   git commit -am 'Add some feature'
   ```

4. Push your changes to your fork:

   ```bash
   git push origin feature/your-feature-name
   ```

5. Create a pull request detailing your changes.



---

Enjoy seamless video conferencing with your friends using the **Django Video Chat** project! If you have any questions or need assistance, feel free to contact me at salmanmehboob610@gmail.com
