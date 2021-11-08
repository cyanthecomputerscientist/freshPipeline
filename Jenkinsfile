@Library('piper-lib-os') _
node() {
    stage('prepare') {
        checkout scm 
        setupComminPipelineEnviorment script: this
    }
    stage('build')
    {
        mtaBuild script: this
    }
}