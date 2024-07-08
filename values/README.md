# To create the secret containing the hugging-face-token

```
kubectl -n chornberger-llama-cpp create secret generic hugging-face-token --from-literal token=hf_abc123def
```