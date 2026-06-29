# codecouncil-test
API_KEY = "sk-1234567890"
query = f"SELECT * FROM users WHERE id = {user_id}"
token = request.args.get('token')
db.execute("SELECT * FROM admin WHERE token=" + token)
