Automated-Plagiarism-Detection-System

Team member details:
1) Krish Sureja
2) Harshit Sajjanapu
3) Shammruth Bhuma

Supervisor: Anuradha Ma'am

Abstract:
Identifying copied content across textual documents efficiently requires fast, computationally optimized string comparison algorithms. This project presents an automated Plagiarism Detection System designed to evaluate multiple documents by generating polynomial hash values and locating matching text segments. By leveraging rolling hash techniques (such as the Rabin-Karp algorithm), the system processes sliding text windows in O(N) time complexity, enabling rapid multi-document comparison.

To ensure precision, the backend engine strictly handles hash collisions by performing direct string verifications whenever matching hash values are detected. The platform automatically calculates and reports similarity percentages across document pairs and renders an intuitive visualization interface that highlights duplicated passages in real time. Developed with a React.js frontend for dynamic text highlighting, a Node.js execution server for hash computation, and MongoDB for document storage, this project demonstrates an end-to-end implementation of efficient document comparison and collision handling techniques.
