library identifier: 'ci-pipeline@master',
        retriever: modernSCM([$class: 'GitSCMSource', remote: 'https://github.com/ci-pipeline/ci-pipeline.git'])

node {
  checkout scm
  ci('.ci-pipeline.yaml')
}

