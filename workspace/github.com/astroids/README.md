Need Pythin 3.10+, uv project and package manager, unix shell

1 - Create a new uv project on your computer.
uv init your-project-name
cd your-project-name

2 - Create a virtual environment at the top level of your project directory
uv venv

3 - Activate the virtual environment
source .venv/bin/activate

4 - Add the pygame library as a project dependency
uv add pygame==2.6.1

5 - Make sure pygame is installed
uv run -m pygame

