
echo 'Hello from jenkins multi-branch pipeline test'

node('master') {
    echo "$BRANCH_NAME"
    sh "npm install"
    sh "mkdir -p Docs.E2E"
    // git url: 'ssh://mseng@mseng.visualstudio.com:22/VSChina/_git/Docs.E2E', branch:'develop'
}
