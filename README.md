# James Palmer

[Functional Programming](#functional-programming) | [Experience](#experience) | [Education](#education) | [Projects](#projects) | [Other Programming](#other-programming)
 
I am a Mathematics graduate, who moved into software after finding inspiration in the Computational Modelling section of my course. A functional developer and machine learning enthusiast, I have been working professionally as a back end Scala engineer since August 2019.

## Functional Programming

### Languages/Libraries

- Scala
  - Cats, Cats Effect IO, ZIO, Simulacrum, Refined, Monocle
- Elm
  - Reactor, Parcel
- Scala JS
  - React
- HTTP4s
  - HTTP library for Scala
- Circe
  - JSON library
- Doobies
  - Functional Database Layer
- FS2
  - Functional Streams for Scala  
- Pure Config
- ScalaTest
- Spark
  - Big data framework

### Project Tools

- AWS
  - S3
  - Cloudfront
  - Lambda
- Docker
- Rabbit MQ
- Kafka
- Jenkins
- Grafana
- Kibana
- OnboardHQ
- Stripe

## Experience 

#### ITV, Junior (08/19 - 04/21), Core (04/21 - Present)

My role extended to microservice architecture and supporting fellow engineers. I initially worked on our content third party streaming integrations, helping to design Aggregate - Transform - Load  solutions with said third parties.
We delivered new functionality for Britbox in line with our product team requirements, including promotional video content  which could be uploaded from our CMS system.
This time included an early adoption of Scala3, which I had prepared for by studying Dotty.
I was then made part of a small cross functional team, where we were tasked with implementing a new streaming feature for our new live streaming strategy. This involved integrating with a third party video streaming platform, building a traffic tolerant EPG service behind AWS Cloudfront, and providing an api for our advertising server.
My most recent workstream has been focused around live content, transitioning architecture and new value propositions.
As part of a pathway to Senior developer, I have been leading projects on behalf of the back end department in our cross functional team. This has included a large internal project in which I worked with architects on a redesign, before mapping out a full quarterly plan with product, along with a third party project in which I have been the backend representative. 
I also engage in our out of hours on call process.

#### ITV, Junior (08/19 - 04/21)

Upon joining ITV, I worked on a new image rendering service for ITV Hub. The stack included at the time bleeding edge scala library ZIO, and frontend language ELM. 
After 5 months I moved to our SVOD team to work on Britbox. Here I was tasked with delivering a number of third party billing integrations. 
I then helped reshape our image pipeline for a major third party streaming integration. Here I integrated our services using Apache Kafka

## Work approach

### Agile

I am comfortable working within an agile environment, with a focus on continuous delivery. This has involved Github Actions and Jenkins, with Docker to spin up local containers.

In my time we have worked under both Kanban and Scrum approaches. As developers we have regularly scrutinised our approaches on a micro level.  My experience has been one of regular delivery dates, launching new features in line with business marketing pushes. At ITV, we had ownership of deployment and testing; encouraging a fail fast environment. We also ran and monitored our own logs and metrics, with Kibana being a preferred debugging tool before a transition to Prometheus.

I’ve worked with both Jira and Confluence for project organisation. 

Working in a greenfield space for a brand new website launch, along with being part of a team responsible for an early stage Britbox, provided valuable experience in a product launch environment.

### Technical

I have gained a lot from working within a structure that supports open source, resulting in  early adoption of new technologies. Two great examples of this are ZIO & Scala3.

I have a very strong understanding of Cats & Cats effect, having first started to study the libraries in 2018.  I’ve been fortunate enough to complete  a Cats Effect course under my company’s personal development budget. Off the back of my university experience, I invested a lot of time into the more abstract category theory, giving me a solid foundation to work from. Cats library has been at the core of my work life, and is an approach I continue to invest time into.

I have multiple years of experience with both HTTP and event streaming. For http, the approach has been to use HTTP4s. Event streaming has mainly been the use of Apache Kafka, using a combination of FS2 and Vulcan as Scala wrappers.

I have extensive experience with SQL/PSQL, with Doobie being the common Scala wrapper used. 

As my experience has increased, I have become much more involved in the designing of our system architecture, helping architects to create requirements. 

On a more personal flavour, I like to code pragmatically within the functional paradigm. MonadError has been my favoured approach to error handling, although I am experienced with other approaches, the general premise remains the same. Test driven development is a fundamental approach to meeting requirements, and I like to include property based testing where appropriate.

### Hollistic

Knowledge sharing is important to me. I am always happy to offer help, particularly junior developers, whilst also willing to ask questions to progress my own understanding. My most recent experience has been to mentor a junior developer in my team. 

To be part of a company that enables extra curricular learning is important to me. I have attended Cats workshops, multiple ScalaCons and completed online courses using training budget at every opportunity in my career so far I have engaged with community projects such as London Scala User Group and Scala Days.. I also invest my own personal time into completing different books and courses.

I have spent the majority of my career in a mostly remote environment. In this respect, I am well prepared for remote environments, and well invested in my personal working environment. I have shown an independence that allows me to continue delivering whilst working remotely. However, my hope is to be part of a vibrant office atmosphere where possible, with extra curricular social events. 

I recently attended the AWS Summit London; opportunities like this are something I will always try to make use of.

## Education

#### Makers Academy (04/02/19 to 04/06/19)

After enjoying the Computational Modelling section of my university course, I spent 08/18 - 01/19 learning how to code from home, using different resources such as Safari Online, Underscore and Coursera. I joined Makers Academy (a 16 week intensive bootcamp) 02/19, deciding it was the perfect opportunity to dedicate myself to software development, gaining qualification and experience.
 
#### Newcastle University (09/15 to 06/18)

- Mathematics, with a focus on Calculus
  - Final modules include Quantum Mechanics, Computational Modelling, Coding Theory, Topology, Relativity & Cosmology.

#### Sixth Form (Graduated 07/15)

###### A-Levels
- Further Mathematics
- Mathematics
- Economics

###### AS Levels
- Sport Studies

 
## Projects 

### Scala

I am constantly taking advantage of resources to improve my technical skills and widen my overall development perspective. In that resepct, I regularly use my Github as a dumping ground of information, exercises, and examples of patterns. 

| **Project Title** | **Description** | **Technologies** | **Testing** |
| :---:        |     :---:      |      :---:    |     :---:      |
| [Essential Scala Workshop](https://github.com/jpalmerr/essential-scala-code)| Whilst at ITV, I completed a 3 day workshop hosted by Underscore's Dave Gurnell  | Scala | Scala Test |
| [Scala with Cats](https://github.com/jpalmerr/ScalaWithCats)| Scala with Cats book  | Scala, Cats | - |
| [Cats exercises](https://github.com/jpalmerr/scalaExercisesCats)| Completed Scala exercises for Cats  | Scala, Cats | - |
| [TypeLevel Cats](https://github.com/jpalmerr/TypeLevel)| TypeLevels category theory exercises  | Scala, Cats | - |
| [Essential Effects](https://github.com/jpalmerr/EssentialEffects) | Cats Effect thorough guide| Scala, Cats, Cats Effect| - |
| [FP for Mortals with Cats](https://github.com/jpalmerr/FpForMortals)| [FP book](https://leanpub.com/fpmortals-cats)  | Scala, Cats, Mouse, Simulacrum | - |
| [Circe Exercises](https://github.com/jpalmerr/CirceExercises) | Completed Scala exercises for Circe | Scala, Circe, Monocle | - |
| [FS2 Course](https://github.com/jpalmerr/FS2Udemy) | Completed FS2 Streams course | - |


#### Areas of Personal Interest

Extra Courses: 

 - [The Data Science Course](https://www.udemy.com/course/the-data-science-course-complete-data-science-bootcamp)
 - [Udacity Course](https://eu.udacity.com/course/intro-to-machine-learning--ud120) to better understand Machine Learning, applying key statistical principles such as Bayes Theorem. 
 - [Coursera Course](https://www.coursera.org/learn/scala-spark-big-data/home/welcome) to learn [Spark](https://github.com/jpalmerr/Spark) in Scala.
 - [Go Course](https://github.com/jpalmerr/GoLand)

| **Project Title** | **Description** | **Technologies** | **Testing** |
| :---:        |     :---:      |      :---:    |     :---:      |
| [AI Pictionary](https://github.com/jpalmerr/ajak-final-project)| An AI trained using neural networks to recognise a user's doodle and return a prediction, deployed [here](https://ajak-doodler.herokuapp.com/) | Python, SKlearn, TensorFlow, Keras, Javascript, jQuery, Flask, Travis, Heroku| Pytest, Capybara, Splinter|
| [MAS3807 Project](https://www.slideshare.net/slideshow/embed_code/key/eY4WwFEd23HUkZ)| Assessed University Project on the effectiveness of differential methods | Fortran| Recieved a grade of 68.9%|
 
## Other Programming 

#### Languages

- Python
  - SKlearn (Machine Learning Library)
 - Go  
- Java
- Ruby
- Matlab
- RStudio

#### Front end & Frameworks

- JavaScript
- Sinatra, RackUp
- CSS, JQuery
- Flask
- Rails

#### Databases

- PSQL
- SQL
