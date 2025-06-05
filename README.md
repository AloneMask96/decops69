https://drive.google.com/drive/folders/1wuKidzkLKnKsOANArQoSdH4q0ZNbIvjY


tasks.register<JavaExec>("run") {
    mainClass.set("com.project.app.App")
    classpath = sourceSets["main"].runtimeClasspath
}
