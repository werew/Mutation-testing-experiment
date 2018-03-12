# Mutation-testing-experiment
Material and results for the mutation testing effectiveness assignment for the "Software Testing and Reverse engineering " course: https://www.4tu.nl/cybsec/en/course-program/str/

The file `ASSIGNMENT.md` contains a description of the assignment as it was provided by the 
teacher. If you are interested in reading my work you have a look at `4.pdf`.

## How to easily generate the reports

I made the reports available at the folder reports but if for any reason you are interested 
in re-generating the reports you can easily do it by following this steps:

Step 1: clone this repository and unpack the file `projects.zip`
```
git clone https://github.com/werew/Mutation-testing-experiment.git
cd Mutation-testing-experiment
unzip projects.zip
```

Step 2: make sure you have everything that you need to build the projects
```
sudo apt-get install openjdk-8-jdk
sudo apt-get install openjdk-8-jre
sudo apt-get install maven
```

Step 3: use the provided script to run all tests
```
cd projects
./run_all_tests.sh
```
