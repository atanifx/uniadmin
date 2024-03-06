# Overview
This package helps to get student admission data from the University of Port Harcourt website.

# Getting Started 
```
pip install uniadmin
```
Or Clone Repo
```
git clone https://github.com/atanifx/uniadmin
```
# Sample usage

```
d = Details()
student_info = d.get_student_details()
d.to_csv(student_info)
```
