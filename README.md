# Programming for the Humanities E22 #

This repository contains all of the code and data related to the Fall 2022 (E22) course _Programming for the Humanities_ which is an [internationalisation elective](https://kursuskatalog.au.dk/da/course/114061/Programming-for-the-Humanities) at [Aarhus University](https://international.au.dk/), [Faculty of Arts](https://arts.au.dk/en/). The course is taught by [Center for Humanities Computing Aarhus](https://chcaa.io/#/), any inquiries can be addressed to [CHCAA](https://chcaa.zendesk.com/hc/en-us/requests/new)

This repository is in active development, with new material being pushed on a weekly basis.
## Technicalities

For running in virtual environment (recommended) and assuming python3.6+ is installed.

```bash
$ sudo pip3 install virtualenv
$ virtualenv -p /usr/bin/python3 venv
$ source venv/bin/activate
```

### Installation

Clone repository and install requirements

```bash
$ git clone https://github.com/CHCAA-EDUX/Programming-for-the-Humanities-E22.git
$ pip3 install -r requirements.txt
```

#### GPU acceleration

[TBA] for your desired CUDA version.

## Repo structure

This repository has the following directory structure:

```sh
.
├── assignments
├── CURRICULUM.md
├── dat # data for exercises and assignments
├── doc # relevant documents
├── examples # examples notebook
├── exercises # tasks for code cafés
├── lessons # lecture lessons in md 
├── reading # readings for lectures
├── LICENSE.md
├── README.md
├── slides # slides from class in pdf
└── src # py code snippets
```

## Course overview and readings

See [Curriculum](https://github.com/CHCAA-EDUX/Programming-for-the-Humanities-E21/blob/main/CURRICULUM.md)

## Contact details

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :smiling_imp:

## Versioning


## Authors
Kristoffer L. Nielbo

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

Al Sweigart
