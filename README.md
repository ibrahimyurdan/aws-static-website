# AWS Static Website Project

A modern, responsive static website hosted on AWS S3, showcasing cloud hosting capabilities and modern web development practices.

## 🌐 Live Demo
[View Live Website](http://aws-static-website-project1.s3-website.us-east-2.amazonaws.com)

## 🚀 Features

- **AWS Cloud Hosting**
  - S3 Static Website Hosting
  - IAM Security Policies
  - CloudFront Ready

- **Modern Development**
  - HTML5 Semantic Elements
  - CSS3 with Flexbox & Grid
  - Vanilla JavaScript (ES6+)

- **Responsive Design**
  - Mobile-First Approach
  - Fluid Typography
  - Adaptive Layouts

- **Performance Optimized**
  - Fast Loading Times
  - Smooth Animations
  - Optimized Assets

## 🛠️ Technologies Used

- AWS S3 for hosting
- HTML5
- CSS3
- JavaScript
- Font Awesome Icons
- Git & GitHub

## 🏗️ Project Structure

```
.
├── index.html          # Main webpage
├── styles.css         # CSS styles
├── script.js          # JavaScript functionality
└── README.md          # Project documentation
```

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/ibrahimyurdan/aws-static-website-project1.git
   ```

2. Open `index.html` in your browser to view locally

3. To deploy to AWS S3:
   - Create an S3 bucket
   - Enable static website hosting
   - Upload all files
   - Configure bucket policy for public access

## 📝 AWS S3 Bucket Policy

Use this bucket policy for public access:

```json
{
    "Version": "2012-10-17",
    "Statement": [
        {
            "Sid": "PublicReadGetObject",
            "Effect": "Allow",
            "Principal": "*",
            "Action": "s3:GetObject",
            "Resource": "arn:aws:s3:::your-bucket-name/*"
        }
    ]
}
```

## 🔒 Security

- Implemented AWS security best practices
- Secure bucket policy configuration
- HTTPS ready (when using with CloudFront)

## 👤 Author

**Ibrahim Yurdan**
- GitHub: [@ibrahimyurdan](https://github.com/ibrahimyurdan)
- LinkedIn: [ibrahim-yurdan](https://linkedin.com/in/ibrahim-yurdan)

## 📄 License

This project is open source and available under the [MIT License](LICENSE). 