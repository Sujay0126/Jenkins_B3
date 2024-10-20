pipeline{
  agent any
    stages{
      stage('Compile'){
      steps{
        bat 'javac Index.java'

      }
    }
      stage('Run'){
      steps{
        bat 'java Index'

      }
    }
  }
}





// Exp 8 (Trigger): 
// Steps : Step 1:click on new Item on admin dashboard and create pipeline project
//         Step 2:Add some build parameters by selecting `This project
//         Step 3:Then select `Trigger build remotely` . This option will
// enable you to build the job by using the URL only other
// browsers or scripts .
//         Step 4: Now write declarative Jenkins pipeline . Here in this
// pipeline i am printing the username who is building it and
// creating a file. Click on SaveStep 6: if TestNG Result is not installled then install it from available plugins
//         Step 5: go to plugins . Install a plugin from available plugins
// called `Build Authorization Token Root`.
//       Step 5: Now use the URL provided below and open it in
// another browser . The moment you opened the URL , this will
// automatically trigger to start the build process of the job

// http://localhost:8080/buildByToken/buildWithParameters?token=54321&job=<name_of_ur_job>
// &whoami=pranit&filename=test.txt
//       Step 6: You can see the building of job successfully completed
// on the Jenkins dashboard .Observe the outputs in console
// output
//       Step 8:In the workspace you will also observe that a filename 



// Pipeline Code: 
// pipeline{
//     agent any

//     stages{
//         stage('Author name'){
//             steps{
//                 echo "This job is executed by ${params.whoami}"   
//             }  
//         }
//             stage('creating file'){
//                 steps{
//                     echo "Filename: ${params.filename}"
//                     echo "Creating....."
//                     bat "echo 'hello geeks' > ${params.filename}"
//                     echo "file is created!!"   
//                 }   
//             }   
//     }
// }



// Exp 7 (Junit and jenkins):

// Step 1: Check your jdk version and maven version
// Step 2: Login Jenkins admin and go to manage jenkins > Tools
// Step 3:set the JDK path in Jenkins as shown below
// Step 4:set the maven path in Jenkins as shown below & Click on the Apply
// Step 5:Click on the Manage Jenkins>Plugins
// Step 6:Click installed plugin and check if TestNG Result is installled or not.
// Step 6: if TestNG Result is not installled then install it from available plugins
// Step 7:Create a new FreeStyle project.Give the Name of the project –
// JUnitReport_Demo.Click on the Freestyle project.
// Step 8:Select a custom workspace and provide the full path of the project.
// Step 10:In the Build Steps section, select Invoke top-level Maven targets.
// Step 11:In the Build Steps section, select Invoke top-level Maven targets.
// Step 12: Provide the full path to pom.xml
// Scroll down to “Post Build Actions” and click on the “Add Post Build Actions” drop- down list. Select “Publish JUnit test result report“.
// Enter the Result Path as “**/target/surefire-reports/*.xml”. Click on the
// Apply and Save buttons
// Execute the tests by clicking on the “Build Now” button. 
