# How to Add an Image and Python Code to GitHub
## 1. Clone the Repository
```bash
git clone https://github.com/USERNAME/REPOSITORY.git
cd REPOSITORY
```
## 2. Add an Image
Add your image to the repository folder.
Project Structure:
```text
REPOSITORY/
├── images/
│   └── sample.png
└── README.md
```
![alt text](Image/image.png)

Display the Image in README.md:
```markdown
Holding shift to drag the image to the desired location
![Sample Image](images/sample.png)
```
## 3. Add Python Code
Create a file named `main.py` and add the following code:

```python
print("Hello, GitHub!")
print("My Python code is added successfully.")
```
## 4. Push Changes to GitHub
```bash
git add -A
git commit -m "Add image and Python code"
git push origin main
```
## Done!
Your image and Python code are now uploaded to GitHub!
![alt text](Image/image.png)

#### Note: Replace `USERNAME` and `REPOSITORY` with your actual GitHub details. Make sure you have permission to push changes to the repository.
