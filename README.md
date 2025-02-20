## How to Run

1. Clone the repository and navigate to the project directory:  
   ```sh
   git clone https://github.com/akildevs1000/wa-proxy-client.git
   cd wa-proxy-client
   ```
2. Install dependencies:  
   ```sh
   npm i
   ```
3. Start the client with your unique string:  
   ```sh
   node client [your_unique_string]
   ```
4. Scan the QR code.  
5. Use via API:  

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