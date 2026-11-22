<!--
  Pull Request Template (compatible con agentes de IA)
  Colocar en: .github/PULL_REQUEST_TEMPLATE.md (raíz del repo)
  Sirve para cualquier repo y cualquier tipo de cambio
  (feature, fix, refactor, docs, CI, config, etc.).
-->
## Motivación — ¿Qué aporta este PR?
<!-- El porqué: qué problema resuelve o qué valor agrega. Si no aporta nada
     claro, quizá el PR no debería existir. Máx 5 líneas. -->
- Problema / necesidad:
- Qué aporta:
- Tipo de cambio: <!-- feature | fix | refactor | docs | CI | config | otro -->

## Resumen
<!-- Qué cambió, sin entrar en el cómo. Máx 3 líneas. -->
Closes #

## Contexto para el agente
<!-- Lo que un humano no necesita leer pero la IA sí: decisiones tomadas,
     alternativas descartadas, restricciones del repo. -->
- Task/issue de origen: #
- Enfoque elegido: <!-- ej: "usé el parser existente, no lib nueva" -->

## Cambios
<!-- Una línea por cambio, archivo o módulo afectado entre backticks. -->
- 

## Cómo probarlo
<!-- Comandos EXACTOS, copy-paste, ajustados a este repo. Sin "correr los
     tests" a secas. Borrar la sección si no aplica (docs puros). -->
```bash
# comando de build/test relevante para este repo
```

## Verificación (evidencia)
<!-- El agente pega aquí la salida real: no descripciones. Si un humano
     hace el PR, marca lo que verificó. -->
- Comando ejecutado:
- Salida:
- Exit code:

## Screenshots
<!-- Si aplica: antes/después para cambios visuales. -->

## Checklist
- [ ] Build y tests del repo pasan
- [ ] Evidencia de verificación pegada arriba
- [ ] Sin warns nuevos del linter
- [ ] Docs actualizadas si cambió la API/comportamiento
- [ ] Rompe compatibilidad hacia atrás → <!-- sí: explicar plan de migración / no -->

---
<!-- Firma del agente, convención para PRs generados por IA -->
🤖 Generated with [Hermes Agent](https://hermes-agent.nousresearch.com)
Co-Authored-By: Hermes <noreply@hermes.dev>
