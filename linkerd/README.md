# Linkerd Service Mesh

Installé manuellement via CLI (edge-26.6.3, seul canal disponible actuellement).

Namespaces meshés (annotation `linkerd.io/inject=enabled`) :
- eksmedz-dev
- eksmedz-staging

Namespaces volontairement exclus du scope (limite de capacité du cluster observée
lors du déploiement sur les 4 environnements simultanément — cf rapport Phase 6) :
- eksmedz-prod
- default

CLI: linkerd, linkerd viz (extension observabilité)
