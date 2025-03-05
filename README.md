# Document_Scanner
A Flask-based web application for scanning and matching text documents, with user authentication, credit system, and admin analytics.



App-Features👍👌
- User Authentication: Register and log in to access the app.
- Document Scanning: Upload `.txt` files to scan for similar documents (1 credit per scan, 20 credits daily).
- Document Matching: View matches for uploaded documents based on text similarity.
- Document Management: Delete or download uploaded documents from the "Past Scans" section.
- Credit System: Request additional credits; admin can approve/deny requests.
- Analytics Dashboard: View system-wide analytics (scans per day, common topics, top users, credit usage) accessible to all users.
- Admin Features: Manage credit requests via `/admin/credits`.


🌐 Project Setup Instructions
1. **Clone the Project**:
   - Ensure the project is on your local machine (e.g., `C:\Users\rakes\OneDrive\Desktop\document_Scanner`).

2. **Install Dependencies**:
   - Install Python 3.x and pip.
   - Install Flask:
     ```bash
     pip install flask

     

     
