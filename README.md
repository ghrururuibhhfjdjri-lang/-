# -from flask import Flask

app = Flask(__name__)

@app.route("/")
def home():
    return """
    <h1>همیار باهنر</h1>
    <p>چت‌بات فارسی در حال راه‌اندازی است.</p>
    """

if __name__ == "__main__":
    app.run()
چت‌بات فارسی همیار باهنر
