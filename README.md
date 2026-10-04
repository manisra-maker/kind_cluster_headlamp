# Headlamp AI Intergration 

Run the Headlamp deployment file and under plugins we will find AI plugins select openAI compatible and add key and model and it will work

In order to access Headlamp in browser run 

```bash
kubectl port-forward -n kube-system svc/headlamp 8081:80
``` 

Then proceed to login via this command 

```bash
kubectl create token headlamp-admin -n kube-system                                                            ─╯
```

Then proceed to open plugins via head lamp UI 

![](assets/2026-10-04-18-20-22.png)
Once thats done click on the assistant and add details 


![](assets/2026-10-04-18-22-37.png)

Finally check via the AI message panel 


![](assets/2026-10-04-18-27-37.png)

