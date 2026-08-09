# Reflection Document
**Name:** Abhinav Mishra
**Roll No:** 24AI004

## Experience and Learning
This lab provided a practical and eye-opening introduction to MLOps. Before this lab, my primary focus was on building machine learning models (the algorithms themselves). Exploring the MLOps ecosystem highlighted that the actual model code is only a small fraction of a production ML system. I learned about the importance of reproducibility, the dangers of training-serving skew, and how tools like MLflow help track experiments systematically.

Setting up the development environment independently rather than following step-by-step classroom instructions was challenging but rewarding. It simulated a real-world scenario where developers often rely on official documentation to configure their environments and resolve issues. 

## Challenges Faced
1. **Virtual Environments**: Setting up the Python virtual environment and managing dependencies properly without polluting the global system packages. Understanding the PEP 668 changes in recent Python versions reinforced the necessity of using `venv` or `conda`.
2. **Tool Integration**: Connecting the various pieces of the ecosystem (Git for version control, VS Code for IDE, and MLflow for experiment tracking) required understanding how these tools communicate.
3. **Documentation Navigation**: Finding the right installation commands and understanding the configuration options in the official documentation of Docker and MLflow took some time but improved my ability to read technical docs.

## Conclusion
Overall, this lab successfully bridged the gap between traditional software engineering principles and machine learning. I now understand why DevOps practices need to be adapted for ML (MLOps) and how tools like MLflow help orchestrate the model lifecycle from tracking experiments to maintaining a model registry.
