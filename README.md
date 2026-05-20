# Kubernetes-CKA

This repository contains practice Kubernetes manifests used for preparing for the Certified Kubernetes Administrator (CKA) exam.

## Contents

- `pod.yaml` - a simple Pod manifest running an `nginx` container.
- `replicaset.yaml` - a ReplicaSet manifest that manages two replicas of an `nginx` Pod.

## Usage

Apply the example manifests to a Kubernetes cluster with:

```bash
kubectl apply -f pod.yaml
kubectl apply -f replicaset.yaml
```

Verify the resources:

```bash
kubectl get pods
kubectl get replicaset
```

## Notes

- `pod.yaml` demonstrates a basic Pod definition.
- `replicaset.yaml` demonstrates a ReplicaSet with label selectors and a Pod template.

Use this repository for hands-on Kubernetes practice and CKA exam preparation.
