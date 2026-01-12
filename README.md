SPRING BOOT PROJECT

RESOURCES
- Packaging : Jar
- Project type : Maven
- Thymeleaf
- Spring Boot
  
DEPENDENCIES
- Thymeleaf
- Lombok
- Spring web

DESCRIPTION

- Once the project is running,the browser sends a request to http://localhost:8080/greeting?name=Vistula
- The spring calls the greeting() controller
- The Controller class is responsoble for adding the name to the model
- Thymeleaf is used to display the data on theweb browser that is passed from the controller.It replaces the name and resolves th:src
- An image is added and stored in the images file within the file tree src/main/resources/static/ and is displayed on the web browser.

  <img width="1308" height="924" alt="Screenshot 2026-01-12 193156" src="https://github.com/user-attachments/assets/243bf31b-58de-4c69-a942-ff867a8f0279" />
