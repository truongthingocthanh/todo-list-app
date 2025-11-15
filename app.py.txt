# A list to store the tasks
tasks = []
def add_task(task_name):
    """Adds a new task to the list."""
    tasks.append(task_name)
    print(f"Added task: '{task_name}'")
# --- Program's starting point ---
if __name__ == "__main__":
    print("Welcome to the To-Do List app!")
    add_task("Learn Git and GitHub")
    add_task("Do the homework practice")