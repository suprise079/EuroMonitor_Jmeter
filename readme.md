# Euro Monitor Assessment - JMeter Performance Script

## 📌 Project Overview

This repository contains a **JMeter performance test script** for the **Euro Monitor Assessment**. The script is designed to simulate load testing scenarios and generate detailed performance reports.

## 📂 Clone the Repository

To get started, clone the repository using the following command:

```sh
git clone https://github.com/suprise079/EuroMonitor_Jmeter.git
```

Navigate to the project directory:

```sh
cd EuroMonitor_Jmeter
```

## 🚀 Running the Performance Test

Execute the following command to run the JMeter test in **non-GUI mode**:

```sh
jmeter -n -t BlazeDemo_Perfomance.jmx -l results.jtl -e -o ReportFolder
```

### Explanation of the Command:

| Command                       | Description                                        |
| ----------------------------- | -------------------------------------------------- |
| `-n`                          | Run JMeter in **non-GUI mode**                     |
| `-t BlazeDemo_Perfomance.jmx` | Specifies the **test plan file** to execute        |
| `-l results.jtl`              | Saves the **test results** in a JTL file           |
| `-e`                          | Generates an **HTML report** from the test results |
| `-o ReportFolder`             | Specifies the **output folder** for the report     |

## 📊 Viewing the Report

After execution, find the performance report in the **ReportFolder**:

1. Open the `ReportFolder` directory.
2. Locate `index.html`.
3. Open `index.html` in a browser to view the detailed performance report.

## 🛠 Prerequisites

Ensure you have the following installed:

- [Apache JMeter](https://jmeter.apache.org/download_jmeter.cgi)
- Java (JMeter requires Java to run)

## 📌 Notes

- Modify the **Thread Group settings** in `BlazeDemo_Perfomance.jmx` to adjust load parameters.
- Ensure JMeter is added to your **system path** to run commands directly.

---

📌 **Author:** [suprise079](https://github.com/suprise079)  
📌 **License:** MIT
