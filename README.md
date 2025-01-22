# Messenger - Laravel Chat Application

Messenger is a Laravel-based real-time chat application designed to provide seamless communication between users. With modern features like instant messaging, group chats, and multimedia sharing, Messenger is perfect for personal and professional use.

---

## Features

- **Real-Time Messaging**: Enjoy instant communication powered by WebSockets.
- **File Sharing**: Share images, videos, and documents within chats.
- **Read Receipts**: Know when your messages have been seen.
- **Typing Indicators**: See when someone is typing a message.
- **Push Notifications**: Get notified about new messages even when offline.
- **User Status**: Display online/offline status for users.
- **Search Conversations**: Quickly find messages and users.
- **Secure Communication**: End-to-end encryption for private chats.
- **Responsive Design**: Fully optimized for mobile and desktop use.

---

## Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-repo/messenger.git
   cd messenger
   ```

2. **Install Dependencies**
   ```bash
   composer install
   npm install
   ```

3. **Set Up Environment**
   - Copy the `.env.example` file to `.env`.
   - Configure your database and other settings in the `.env` file.

4. **Run Migrations**
   ```bash
   php artisan migrate
   ```

5. **Generate Application Key**
   ```bash
   php artisan key:generate
   ```

6. **Install WebSocket Server**
   - Configure WebSockets using Laravel Echo and Pusher (or your preferred WebSocket server).

7. **Start the Application**
   ```bash
   php artisan serve
   npm run dev
   ```

---

## Usage

1. **User Registration**
   - Sign up or log in to access the chat application.

2. **Start a Conversation**
   - Search for users and start a private chat or create a group chat.

3. **Send Messages**
   - Use the chat interface to send text, emojis, and multimedia files.

4. **Manage Groups**
   - Add or remove participants, change group names, and update group settings.

5. **Enable Notifications**
   - Allow push notifications for instant updates.

---

## Compatibility

- PHP 8.0+
- Laravel 9+
- MySQL 5.7+
- Redis (for real-time messaging)
- Works with major browsers and devices

---

## Changelog

### Version 1.0.0
- Initial release
- Real-time messaging
- Group chat functionality
- File sharing support

---

## Support

If you encounter issues or have feature requests, please [submit a ticket](#).

---

## License

This application is open-source and free to use for personal and commercial purposes. No license restrictions apply.
