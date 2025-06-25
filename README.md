SwiftFrame README
SwiftFrame
SwiftFrame is a lightweight Python web framework inspired by Flask, Django, and FastAPI. It offers simple routing, middleware, and request handling designed for fast and flexible web apps and APIs.

Features
Easy routing system

Middleware support

Request & response handling

Modular and extensible

Supports sync & async operations

Installation
bash
Copy
Edit
pip install swiftframe
Quick Start
python
Copy
Edit
from swiftframe import SwiftFrame

app = SwiftFrame()

@app.route("/")
def home(request):
    return "Hello from SwiftFrame!"

if __name__ == "__main__":
    app.run()
Contributing
Contributions are welcome! Please open issues or submit pull requests.

License
MIT License
