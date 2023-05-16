![Image](https://camo.githubusercontent.com/d8a348e1fceb92d45fa8981ac42a6223e454acefe89750896e80fd1287cab92b/68747470733a2f2f7777772e706e676974656d2e636f6d2f70696d67732f6d2f3133322d313332323132355f7472616e73706172656e742d6261636b67726f756e642d616972626e622d6c6f676f2d68642d706e672d646f776e6c6f61642e706e67)

---
# DESCRIPTION:microphone:
---
HBnB is a comprehensive web application that combines various components such as database storage, a back-end API, and front-end interfacing, all designed to replicate the functionalities of AirBnB. This marks the initial stage in the development of a complete web application, specifically an AirBnB clone. During this first step, the focus lies on creating a unique command-line interface that allows efficient management of data, along with the foundational classes required to store this data.
`models:`directory will contain all classes used for the entire project. A class, called “model” in a OOP project is the representation of an object/instance.
`tests:`directory will contain all unit tests.
`console.py:`file is the entry point of our command interpreter.
`models/base_model.py: ` file is the base class of all our models. It contains common elements:
     .attributes: id, created_at and updated_at
     .methods: save() and to_json()
`models/engine:`directory will contain all storage classes (using the same prototype). For the moment you will have only one: file_storage.py.
---
# command interpreter :computer:
---
