
# Face Recognition System

This project presents a comprehensive Java-based face recognition system designed to reliably identify individuals despite variations in facial expressions, occlusions such as glasses, and pose changes up to 60 degrees. It leverages the well-established eigenfaces technique combined with a Two-Stage Classification and Detection (TSCD) approach to improve recognition accuracy and robustness under real-world conditions.

The system provides an interactive graphical user interface (GUI) that allows users to load and preprocess face images, train the recognition model, and test it on new data. It supports batch processing for handling multiple images efficiently. To enhance user experience and interpretation of results, the application incorporates 3D visualization of faces and recognition outcomes using the Java 3D API, offering an intuitive spatial perspective.

User information and authentication are managed through integration with a MySQL database, ensuring secure and structured data storage. The application also utilizes Java Advanced Imaging (JAI) libraries to facilitate efficient image processing and manipulation, critical for accurate feature extraction.

## Technologies and Tools Used

* **Java (JDK 8+)**: Primary programming language ensuring portability and rich ecosystem support.
* **Maven**: Build automation tool used for managing dependencies, compiling code, and packaging the application.
* **Eigenfaces Algorithm**: Principal Component Analysis (PCA)-based method to extract key facial features and represent faces efficiently for recognition.
* **Two-Stage Classification and Detection (TSCD)**: A hybrid approach combining detection and classification stages to improve recognition accuracy and reduce false positives.
* **Java 3D API**: Facilitates rendering of 3D face models and visualization of recognition results, enhancing clarity and analysis.
* **Java Advanced Imaging (JAI) Libraries**: Provides advanced image processing functions, enabling effective preprocessing and feature extraction from face images.
* **MySQL Database**: Stores user credentials and application data securely, supporting multi-user scenarios and persistent storage.
* **Swing/AWT GUI Frameworks**: Build an interactive, user-friendly interface for seamless interaction with the system functionalities.

