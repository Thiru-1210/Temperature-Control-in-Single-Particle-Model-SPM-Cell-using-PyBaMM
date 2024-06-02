Temperature Control in Single Particle Model (SPM) Cell using PyBaMM

Project Description:

This project involves developing a temperature control mechanism for a lithium-ion battery cell using the PyBaMM (Python Battery Mathematical Modelling) library. The LG M50 battery model was employed within a Single Particle Model (SPM) framework. A step size reduction method was implemented to dynamically adjust the current, ensuring the battery temperature remains below the safety threshold of 45°C. This approach guarantees optimal performance and safety of the battery.

Key Results:

Effective Thermal Management: Successfully maintained the battery temperature below 45°C, ensuring safety.
Precise Temperature Control: Utilized 81 different current values to achieve precise control over the battery temperature.
Enhanced Battery Performance: Demonstrated effective thermal management, which is crucial for applications in electric vehicles and renewable energy storage.

Significance:

The project underscores the importance of thermal management in lithium-ion batteries to enhance their performance, longevity, and safety. This work contributes significantly to the advancement of sustainable energy solutions and the development of reliable battery technologies. By maintaining optimal temperature conditions, the project promotes the safe and efficient use of lithium-ion batteries in various applications, particularly in electric vehicles and renewable energy storage systems.

Installation and Usage
Clone the Repository:

sh
Copy code
git clone https://github.com/Thiru-1210/temperature-control-spm-cell.git
cd temperature-control-spm-cell
Install Required Libraries:
Make sure you have Python installed. Then, install the necessary libraries:

sh
Copy code
pip install pybamm
Run the Simulation:
Execute the main script to run the temperature control simulation:

sh
Copy code
python main.py
Project Structure
main.py: The main script to run the temperature control simulation.
requirements.txt: List of required Python libraries.
README.md: Project documentation.
Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

License:

This project is licensed under the MIT License - see the LICENSE file for details.

Contact:

For any questions or inquiries, please contact Thiruvenkatanath Balaji at thiruvenkatanath12@outlook.com.
