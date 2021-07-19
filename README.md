# Myers-Briggs personality BERT Classification


# Table of contents

<!-- After you have introduced your project, it is a good idea to add a **Table of contents** or **TOC** as **cool** people say it. This would make it easier for people to navigate through your README and find exactly what they are looking for.

Here is a sample TOC(*wow! such cool!*) that is actually the TOC for this README. -->

- [Myers-Briggs personality BERT Classification](#project-title)
- [Table of contents](#table-of-contents)
- [Installation](#installation)
- [Usage](#usage)


# Installation
[(Back to top)](#table-of-contents)

1. Clone the repo with this command with `git clone https://github.com/AymanSulaiman/myers-briggs-personality.git`
2. In *Anaconda prompt*, navigate to the directory containing the *environment.yaml* and write `conda env create -f environment.yaml`.

3. Activate the new environment with `conda activate ml`.

4. Write `pip install -r requirements.txt`.

This will have your enviornment set up.
```
Note: in the near future I plan to save the bert model, turn the notebooks into scripts, and  build a streamlit app that can be run via a docker container. This will allow users to use the streamlit app without resorting to make an anaconda enviornment.
```


# Usage
[(Back to top)](#table-of-contents)

<!-- This is optional and it is used to give the user info on how to use the project after installation. This could be added in the Installation section also. -->

Once all of the components and files are made as stated above, I want it to be as straight forward as running the docker container and accessing the app through a web browser of your choice.

# Model Drawbacks
The dataset has a lot more personailty type targets that relate to Introverts rather than extroverts so once the model is built, the results will be skewed towards introverted personality types. The best method to avoid this is to have an equal number of personality types in the dataset to avoid that skew. This will be explored soon in the `data cleaning notebook`. 