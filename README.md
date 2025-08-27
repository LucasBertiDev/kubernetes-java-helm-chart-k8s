# kubernetes-java-helm-chart-k8s
Chart padrão para aplicações helm chart

# Para públicar esse chart execute 

# 1) Empacotar o chart
helm package kubernetes-java-helm

# 3) Enviar
helm push ./kubernetes-java-helm-1.0.5.tgz oci://ghcr.io/lucasbertidev/charts
