# Privacy Preserving Data Science
Course Material for the Tutorial on Privacy Enhancing Technologies and PPML

In this tutorial we will go through a series of examples demonstrating the main features of the so-called _Privacy Preserving_ technologies. 

In the first part, we will focus on _Data Anonymisation_ and methods for privacy protection. We will see examples of  _De-Identification_, _K-Anonymity_, and a very short intro to _Differential Privacy_.

In the second part, we will be shifting the focus more on Machine (Deep) Learning, investigating in more details how _Convolutional Networks_ work on Images (using `PyTorch`), and how _susceptible_ these methods are to **Adversarial Attacks**.
The `FGSM` and the `Adversarial-Patches` attacks will be presented (with examples in PyTorch), along with some considerations on possible counter-meausures.

Finally, in the third part, we will introduce some of the main concepts for _Privacy-Preserving Machine Learning_, like _Federated Learning_ and _Homomorphic Encryption_. Two examples on medical datasets will be presented.

**Note**

All references and further suggested readings are reported in each notebook.

  

### Get the material

Clone the current repository, in order to get the course materials. To do so, once connected to your remote machine (via `SSH`), execute the following instructions:

```bash
cd $HOME  # This will make sure you'll be in your HOME folder
git clone https://github.com/WebValley2021ReImagined/privacy-preserving-data-science.git
```

**Note**: This will create a new folder named `privacy-preserving-data-science`. Move into this folder by typing:

```bash
cd privacy-preserving-data-science
```

Well done! Now you should do be in the right location. Bear with me another few seconds, following instructions reported below 🙏

### Updating your Environment

To execute the notebooks in this repository, a few _extra_ packages are required, but installing them in your Conda environment is super easy. 

While into the `privacy-preserving-data-science.git` folder, execute the two following instructions:

```bash
conda activate py38_default  #activate your conda environment
pip install -r requirements.txt  # to install the extra packages
```

🎉 You should be now ready to go!

The last bit is to run your `jupyter lab` server, and open the notebooks:

```bash
jupyter lab
```

## Colophon

**Author**: Valerio Maggio ([`@leriomaggio`](https://twitter.com/leriomaggio)), Senior Research Associate, University of Bristol. 

All the **Code** material is distributed under the terms of the GNU GPLv3 License. See [LICENSE](./LICENSE) file for additional details.

All the instructional materials in this repository is free to use, and made available under the [Creative Commons Attribution
license][https://creativecommons.org/licenses/by/4.0/]. The following is a human-readable summary of (and not a substitute for) the [full legal text of the CC BY 4.0
license](https://creativecommons.org/licenses/by/4.0/legalcode).

You are free:

* to **Share**---copy and redistribute the material in any medium or format
* to **Adapt**---remix, transform, and build upon the material

for any purpose, even commercially.

The licensor cannot revoke these freedoms as long as you follow the
license terms.

Under the following terms:

* **Attribution**---You must give appropriate credit (mentioning that
  your work is derived from work that is Copyright © Software
  Carpentry and, where practical, linking to
  http://software-carpentry.org/), provide a [link to the
  license][cc-by-human], and indicate if changes were made. You may do
  so in any reasonable manner, but not in any way that suggests the
  licensor endorses you or your use.

**No additional restrictions**---You may not apply legal terms or
technological measures that legally restrict others from doing
anything the license permits. 


### Acknowledgment and funding
The material developed in this course has been supported by the [JGI seed corn funding](https://jeangoldinginstitute.blogs.bristol.ac.uk/2021/01/07/seed-corn-funding-winner-announcement/) call 2020-2021

![JGI Logo](./logos/jgi-logo.png "Jean Golding Institute")
![UoB Logo](./logos/uob_logo_small.png "University of Bristol")


### Contacts 

For any questions or doubts, feel free to open an [issue](https://github.com/WebValley2021ReImagined/unsupervised-learning/issues) in the repository, or drop me an email @ `valerio.maggio_at_bristol.ac.uk`

