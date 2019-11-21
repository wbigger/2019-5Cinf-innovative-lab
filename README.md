# Innovative Lab

This is the repository for the new Innovative Lab of IIS G. Marconi, Civitavecchia.

Preferred editor: VS Code.

See also [this doc](https://docs.google.com/document/d/1jmqQJLx6FoIjivqpaGArWUZxyqoeGmkUqydpuCeI0jY/edit?usp=sharing) (ITA) that contains a simulation of a hypothetical State Certification Exam.

## Project Description
### Brief
To encourage the best learning practices for Italian high school students, the Italian Ministry of University and Research intends to promote the renewal of laboratories in schools, equipping them with innovative technological resources and adequate furnishings, in order to enable new teaching methods (group work, flipped classroom, etc.).

To this end, we intend to build an automation infrastructure that allows us to simplify some operations, inspired by Industry 4.0.

### Details
The environment must include the following functional areas:
- workshops, where users can use laptops or write on sheets of paper, billboards and the like
- presentation, in which users can project on the blackboard and the public can listen
- maker, equipped with welders, Arduino, Raspberry PI, components, 3D printer, etc.
- virtual reality, equipped with workstations with viewers to enjoy immersive technologies such as Oculus

For the management of the new laboratory, a website has to be implemented with following features:
- management of environmental lights, independently for each area
- management of borrowing of work material (eg Arduino, Raspberry PI, etc)
- enabling and disabling the internet, independently for the workshop area, the VR area or the entire laboratory
- temperature management, also based on the outside temperature and time intervals
- enabling and disabling a small break area with a coffee machine connected to the network.

We also want to provide the following services to students and teachers within the laboratory:
- device for voice commands for lighting and temperature regulation
- streaming video and audio service between stations, to allow real-time collaboration between people even in different areas of the environment, without disturbing others

## Implementation
The website will be realized with a 3-tiers architecture:
- website
- backend
- MySQL database

The project will rely on the AWS services, since we can take advantage of AWS Educate.


## Assignments
- [Assignment 1](./assignments/assignment-1.md)