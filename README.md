# Welcome to the assesment test
### DO NOT FORK THIS PROJECT

### We have 3 objects:
* A User that can either be a student (if it only learns courses), a teacher (if it only teaches)
or a student_teacher if it does both things

* A Program that represents the subject of a course (Eg: Calculus)

* An enrollment that represents the student and the teacher that are in a certain course 

### Before coming to the first tecnical meeting you:

* CAN NOT CHANGE THE TESTS or MIGRATIONS

* CAN NOT ADD NEW MODELS, CONTROLLERS or MIGRATIONS

* HAVE ALL RSPEC TESTS PASSING, without changing them (you can add more tests if you want)

* Have a basic idea of how the code works

* Understand how models should interact


## Create a candidate copy of the assessment

Replace `CANDIDATE` with a short slug (e.g. `jane-doe`) and `GITHUB_USERNAME` with the candidate's GitHub handle.

### 1. Clone the source as a bare repo

```bash
git clone --bare git@github.com:emeritus-tech/coding-assessment-rails-2026.git
cd coding-assessment-rails-2026.git
```

### 2. Create a private GitHub repo for the candidate

```bash
gh repo create emeritus-tech/coding-assessment-rails-2026-CANDIDATE --public
```

### 3. Push a full copy (all branches and tags)

```bash
git push --mirror git@github.com:emeritus-tech/coding-assessment-rails-2026-CANDIDATE.git
```

### 4. Ensure that you have deleted candidate-repo after the interview

Do not add candidates to `coding-assessment-rails-2026`. Each person gets only their own private copy.
