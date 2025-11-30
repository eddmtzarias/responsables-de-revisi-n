# responsables-de-revisi-ngit checkout -b add-auto-responder
Crear archivos:
.github/CODEOWNERS con:
CODEOWNERS — responsables de revisión
Aplica a todo el repositorio
@eddmtzarias
.github/workflows/auto-responder.yml con el contenido que ya has escrito (flujo de trabajo que comenta y añade la etiqueta 'triage').
git add .github/CODEOWNERS .github/workflows/auto-responder.yml
git commit -m "Agregar CODEOWNERS y flujo de trabajo de respuesta automática"
git push origin agregar respuesta automática
