# Robotic Introduction

An introduction to robotics course for mechanical engineering M2 students.

## Repository Structure

This repository is organized into three main folders:

### 📚 CM - Course Materials (Cours Magistral)
Contains LaTeX Beamer presentations covering the theoretical aspects of robotics:
- Fundamental concepts of robotic systems
- Kinematics and dynamics
- Control theory applications
- Advanced topics in robotics

All presentations are created using LaTeX Beamer and can be compiled to PDF format.

### 📝 TD - Directed Work (Travaux Dirigés)
Contains exercises and their corrections in LaTeX format:
- Problem sets based on course material
- Detailed step-by-step corrections
- Application exercises
- Theoretical problems and solutions

Each TD includes both the exercise sheet and a comprehensive correction document.

### 🔧 TP - Practical Work (Travaux Pratiques)
Contains three practical sessions focused on hands-on robotics implementation:

#### **Session 1**: Introduction to Robotic Systems
- Basic robotic system architecture
- Fundamental programming for robotics
- Development environment setup
- First control programs

#### **Session 2**: Sensors and Actuators
- Sensor interfacing and data processing
- Actuator and motor control
- Feedback control loop implementation
- System calibration

#### **Session 3**: Integration and Testing
- Complete system integration
- Testing and validation procedures
- Performance optimization
- Final project demonstration

## Evaluation Details

### Grading Breakdown

| Component | Weight | Description |
|-----------|--------|-------------|
| **TP Sessions** | 40% | Continuous assessment during practical sessions |
| **TD Participation** | 20% | Active participation and exercise completion |
| **Final Project** | 30% | Complete robotic system demonstration (TP Session 3) |
| **Written Exam** | 10% | Theoretical knowledge assessment |

### TP Evaluation Criteria

Each practical session is evaluated based on:
- **Technical Implementation** (40%): Correctness and quality of code/implementation
- **Documentation** (20%): Clear documentation and comments
- **Demonstration** (30%): Working demonstration of the system
- **Understanding** (10%): Ability to explain choices and troubleshoot

### Final Project Requirements

The final project (TP Session 3) must demonstrate:
1. Complete integration of sensors and actuators
2. Functional control system
3. Robust error handling
4. Clear documentation
5. Live demonstration with Q&A

### Important Dates

- TD sessions: Weekly throughout the semester
- TP Session 1: Week 4
- TP Session 2: Week 8
- TP Session 3 (Final Project): Week 12
- Written Exam: End of semester

## Getting Started

### Prerequisites

For working with course materials:
- LaTeX distribution (TeX Live or MiKTeX)
- PDF viewer
- Text editor or LaTeX IDE

For practical sessions:
- Development environment (details in TP/README.md)
- Access to laboratory equipment
- Programming tools (specified in each session)

### Building LaTeX Documents

To compile presentations and documents:
```bash
cd CM  # or TD
pdflatex document_name.tex
```

For documents with bibliography:
```bash
pdflatex document_name.tex
bibtex document_name
pdflatex document_name.tex
pdflatex document_name.tex
```

## Contact

For questions or issues regarding the course materials, please contact the course instructor or use the repository's issue tracker.

## License

This course material is provided for educational purposes for M2 Mechanical Engineering students.
