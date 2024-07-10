- 👋 Hi, I’m @EETIBDN
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
1) create database webapp1

2) Create table:-

CREATE TABLE users (
  id INT(6) UNSIGNED AUTO_INCREMENT PRIMARY KEY,
  name VARCHAR(30) NOT NULL,
  password VARCHAR(255) NOT NULL,
  phone VARCHAR(20) NOT NULL,
  address VARCHAR(255) NOT NULL,
  email VARCHAR(50),
  photo VARCHAR(255),
  created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
  updated_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP ON UPDATE CURRENT_TIMESTAMP 
);



3) Insert data into the table:-

   INSERT INTO users (name, password, phone, address, email, photo) VALUES
('Aisha Kaur', '$2y$10$92IXUNpkjO0rOQ5byMi.Ye4oKoEa3Ro9llC/.og/at2.uheWG/igi', '9988776655', '123, ABC Street, Mumbai', 'aisha@example.com', 'aisha.jpg'),
('Rohan Sharma', '$2y$10$92IXUNpkjO0rOQ5byMi.Ye4oKoEa3Ro9llC/.og/at2.uheWG/igi', '9876543210', '456, XYZ Apartments, Delhi', 'rohan@example.com', 'rohan.jpg'),
('Priya Singh', '$2y$10$92IXUNpkjO0rOQ5byMi.Ye4oKoEa3Ro9llC/.og/at2.uheWG/igi', '9665443322', '789, PQR Complex, Chennai', 'priya@example.com', 'priya.jpg'),
('Rahul Kumar', '$2y$10$92IXUNpkjO0rOQ5byMi.Ye4oKoEa3Ro9llC/.og/at2.uheWG/igi', '9554433221', '901, MNO Residency, Bangalore', 'rahul@example.com', 'rahul.jpg'),
('Sonia Jain', '$2y$10$92IXUNpkjO0rOQ5byMi.Ye4oKoEa3Ro9llC/.og/at2.uheWG/igi', '9443322110', '234, EFG Flats, Hyderabad', 'sonia@example.com', 'sonia.jpg'),
('Rajeev Kapoor', '$2y$10$92IXUNpkjO0rOQ5byMi.Ye4oKoEa3Ro9llC/.og/at2.uheWG/igi', '9332211009', '567, IJK Villas, Pune', 'rajeev@example.com', 'rajeev.jpg'),
('Swati Mishra', '$2y$10$92IXUNpkjO0rOQ5byMi.Ye4oKoEa3Ro9llC/.og/at2.uheWG/igi', '9221100998', '890, LMN Bungalows, Ahmedabad', 'swati@example.com', 'swati.jpg'),
('Abhishek Gupta', '$2y$10$92IXUNpkjO0rOQ5byMi.Ye4oKoEa3Ro9llC/.og/at2.uheWG/igi', '9110099887', '345, CDE Cottages, Kolkata', 'abhishek@example.com', 'abhishek.jpg'),
('Neha Sharma', '$2y$10$92IXUNpkjO0rOQ5byMi.Ye4oKoEa3Ro9llC/.og/at2.uheWG/igi', '9009887766', '678, ABCD Enclave, Jaipur', 'neha@example.com', 'neha.jpg'),
('Aman Singh', '$2y$10$92IXUNpkjO0rOQ5byMi.Ye4oKoEa3Ro9llC/.og/at2.uheWG/igi', '8898776655', '567, EFGH Residency, Lucknow', 'aman@example.com', 'aman.jpg'),
('Anjali Jain', '$2y$10$92IXUNpkjO0rOQ5byMi.Ye4oKoEa3Ro9llC/.og/at2.uheWG/igi', '8787665544', '456, IJKM Apartments, Bhopal', 'anjali@example.com', 'anjali.jpg'),
('Rohan Mehta', '$2y$10$92IXUNpkjO0rOQ5byMi.Ye4oKoEa3Ro9llC/.og/at2.uheWG/igi', '8676554433', '789, ABCDE Flats, Indore', 'rohanm@example.com', 'rohanm.jpg');

<!---
EETIBDN/EETIBDN is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
