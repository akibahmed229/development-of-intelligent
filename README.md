- https://pypi.org/search - search for the package you want to install in pypi
- https://search.nixos.org/packages - search for the package you want to install in nixpkgs

Here’s a quick guide to using `pip` with a virtual environment:

1. **Create a Virtual Environment**:

   ```bash
   python -m venv myenv
   ```

2. **Activate the Environment**:

   - **Linux/Mac**: `source myenv/bin/activate`
   - **Windows**: `myenv\Scripts\activate`

3. **Install Packages**:

   ```bash
   pip install <package-name>
   ```

4. **List Installed Packages**:

   ```bash
   pip list
   ```

5. **Freeze Dependencies**:

   ```bash
   pip freeze > requirements.txt
   ```

6. **Install from `requirements.txt`**:

   ```bash
   pip install -r requirements.txt
   ```

7. **Deactivate Environment**:
   ```bash
   deactivate
   ```
