# Python MCP Project

This is a Multi-Component Project (MCP) template for Python. It includes multiple Python packages as components, basic unit tests, and CI via GitHub Actions.

## Structure

- `components/`: Contains each component as a Python package.
- `tests/`: Contains test files for each component.
- `.github/workflows/ci.yml`: Continuous Integration workflow.

## Getting Started

1. Create a virtual environment:  
   `python -m venv venv && source venv/bin/activate`
2. Install dependencies:  
   `pip install -r requirements.txt`
3. Run tests:  
   `pytest tests`