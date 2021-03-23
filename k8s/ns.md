
# K8S namespace 删除失败，一直显示 terminating

 kubectl get namespace $STUCKED_NS -o json | tr -d "\n" | sed "s/\"finalizers\": \[[^]]\+\]/\"finalizers\": []/" | kubectl replace --raw /api/v1/namespaces/$STUCKED_NS/finalize -f -
