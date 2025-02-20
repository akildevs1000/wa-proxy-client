## How to Run

1. Install dependencies:
   ```sh
   npm i
   ```
2. Start the client with your unique string:
   ```sh
   node client [your_unique_string]
   ```
3. Scan the QR code.
4. Use via API:

   **Endpoint:**

   ```
   https://wa.mytime2cloud.com/send-message
   ```

   **POST Request:**

   ```json
   {
     "clientId": "AE00012",
     "recipient": "971554501483",
     "text": "Whatsapp service is working"
   }
   ```

   **Response:**

   ```json
   {
     "success": true,
     "data": "Message to 971554501483 is being processed."
   }
   ```