import java.text.SimpleDateFormat

pipeline {
    agent any
    stages{
        stage('showDate'){
            steps{
                script{
                    def fecha = '2022-07-01T09:35:00.000-0000'
                    def formato = "yyyy-MM-dd'T'HH:mm:ss.SSSZ"
                    def parseo = new SimpleDateFormat(formato).parse(fecha)
                    def dia = new Date()
                    println dia
                }
            }
        }
    }
}

