# kubernetes-snippets
Code snippets of kubernetes for visual studio code.

This image shows an example of what you can do with this extension. In 3 words: typing very fast!

![Kubernetes extension example](https://raw.githubusercontent.com/ipedrazas/kubernetes-snippets/master/images/kubernetes-extension.gif "Kubernetes Extension example")

To create secrets, we can just use the template and write them in plain text. Using the key combination of Cmd+k, Cmd+E if you're in OSX (Ctrl if you're in linux/windows) you can encode to Base64.

![Kubernetes Secrets example](https://raw.githubusercontent.com/ipedrazas/kubernetes-snippets/master/images/secrets-extension.gif "Kubernetes Extension example")

You want to decode a secret, the key combination is Cmd + K, Cmd + D.

There are snippets to quickly create `pods`, `services`, `deployments`,etc. As well, there are snippets to 
quickly add parts of the descriptor like `ports`, `cmd` and `volumes`  

For example, if you start typing `bk_` a suggestion will be shown (`deployment, deployment_simple`), if you expand the snippet you will get something like this:




### Extension incompatibillity
This extension is not compatible with the following extensions:

 * vs-kubernetes
 * vscode-helm