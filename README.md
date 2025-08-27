# kubernetes-java-helm-chart-k8s
Chart padrão para aplicações helm chart

# Para públicar esse chart execute 

# 1) Empacotar o chart
helm package kubernetes-java-helm

# 2) Verificar o chart
helm template test-release kubernetes-java-helm

# 3) Enviar
helm push ./kubernetes-java-helm-1.0.1.tgz oci://ghcr.io/lucasbertidev/charts
