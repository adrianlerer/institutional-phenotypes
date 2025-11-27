# 🛡️ PRIVACY FRAMEWORK - SISTEMA OVERHEARING
## IntegridAI Suite - Canal de Denuncias Proactivo

**Versión:** 1.0  
**Fecha:** 26 Noviembre 2025  
**Audiencia:** Compliance Officers, Legal, CISOs, Comités de Ética  
**Propósito:** Documento técnico para clientes enterprise sobre protección de privacidad

---

## 📋 RESUMEN EJECUTIVO

El **Sistema Overhearing** de IntegridAI Suite es un módulo opcional de detección proactiva de compliance issues que monitorea comunicaciones laborales con inteligencia artificial para identificar patrones de riesgo (corrupción, acoso, fraude) **antes de que escalen**.

Este documento detalla cómo el sistema protege la privacidad de los empleados mediante:
- ✅ Anonimización por diseño
- ✅ Cifrado multicapa
- ✅ Acceso restringido y auditado
- ✅ Cumplimiento normativo (Ley 25.326, GDPR, Ley 27.401)
- ✅ Transparencia total hacia empleados

**Concepto clave:** Overhearing NO es vigilancia laboral. Es un sistema de compliance automatizado que protege tanto a la empresa como a los empleados.

---

## 🎯 ¿QUÉ ES EL SISTEMA OVERHEARING?

### **Definición**

"Overhearing" = "Escuchar por casualidad" o "escuchar sin querer"

En el contexto de IntegridAI, es un sistema de **línea de denuncias sin denunciante activo**:
- Detecta automáticamente conversaciones de riesgo (sobornos, acoso, fraude)
- Genera alertas anonimizadas para el Compliance Officer
- NO revela identidades sin aprobación formal
- Funciona como complemento del Canal de Denuncias tradicional

### **Diferencia con Canal Tradicional**

| Aspecto | Canal Tradicional (Reactivo) | Sistema Overhearing (Proactivo) |
|---------|------------------------------|----------------------------------|
| **Iniciativa** | Empleado debe denunciar | Sistema detecta automáticamente |
| **Cobertura** | Solo casos denunciados | Detecta casos no denunciados |
| **Timing** | Post-incidente | Pre-escalamiento |
| **Anonimato** | Depende del denunciante | Anonimato total (no hay denunciante) |
| **Uso típico** | 20-30% de casos | 70-80% de casos (detección temprana) |

---

## ⚖️ BASE LEGAL Y CUMPLIMIENTO NORMATIVO

### **ARGENTINA - Ley 25.326 (Protección de Datos Personales)**

**Artículo 4 - Requisitos para monitoreo:**

El empleador PUEDE monitorear comunicaciones laborales SI cumple:

1. ✅ **Consentimiento explícito del empleado** (Art. 5)
   - Incluido en contrato laboral
   - Renovado anualmente
   - Empleado puede negarse (con consecuencias laborales justificadas)

2. ✅ **Finalidad legítima** (Art. 4.1)
   - Cumplimiento de Ley 27.401 (Responsabilidad Penal Empresaria)
   - Prevención de fraude, corrupción, acoso
   - NO puede usarse para control de productividad o evaluación de desempeño

3. ✅ **Proporcionalidad** (Art. 4.2)
   - Solo se monitorean comunicaciones laborales
   - No se monitorean cuentas personales
   - Minimización de datos (solo lo necesario para compliance)

4. ✅ **Notificación previa** (Art. 6)
   - Empleados deben ser notificados antes de iniciar monitoreo
   - Carteles visibles en lugares de trabajo
   - Avisos en sistemas digitales (email, chat)

**Cláusula de contrato laboral sugerida:**
```
"El empleado presta su consentimiento expreso para que sus comunicaciones 
laborales (emails corporativos, chat interno, reuniones virtuales grabadas, 
llamadas telefónicas laborales) sean monitoreadas por sistemas automatizados 
de compliance con el único fin de detectar violaciones al Código de Ética 
y cumplimiento de Ley 27.401 (Responsabilidad Penal Empresaria).

Los datos personales serán anonimizados por defecto y solo serán 
desanonimizados en caso de investigación formal aprobada por el Comité 
de Ética. El empleado tiene derecho a acceder, corregir o eliminar sus 
datos según lo establecido en la Ley 25.326.

Este consentimiento es obligatorio para el desarrollo de tareas que 
impliquen el uso de herramientas corporativas de comunicación."
```

---

### **EUROPA - GDPR (General Data Protection Regulation)**

**Aplicable si:** La empresa tiene operaciones en la Unión Europea o procesa datos de ciudadanos europeos.

#### **Art. 6 - Base legal para procesamiento:**

✅ **Opción 1: Interés legítimo** (Art. 6.1.f)
- Prevenir fraude y corrupción es un interés legítimo de la empresa
- Debe pasar el "Balancing Test": interés empresarial vs. derechos del empleado

✅ **Opción 2: Obligación legal** (Art. 6.1.c)
- Cumplimiento de leyes anti-soborno (Ley 27.401, UK Bribery Act, FCPA)

#### **Art. 5 - Principios de procesamiento:**

1. ✅ **Minimización de datos** (Art. 5.1.c)
   - Solo guardar lo relevante para compliance
   - Eliminar datos no esenciales

2. ✅ **Limitación de propósito** (Art. 5.1.b)
   - NO usar para control laboral
   - NO usar para evaluación de desempeño

3. ✅ **Limitación de almacenamiento** (Art. 5.1.e)
   - Borrar datos tras investigación
   - Política de retención clara

4. ✅ **Integridad y confidencialidad** (Art. 5.1.f)
   - Cifrado end-to-end
   - Acceso restringido

#### **Art. 35 - Evaluación de Impacto (DPIA)**

IntegridAI provee plantilla de DPIA que incluye:

1. **Descripción del procesamiento**
   - Qué comunicaciones se monitorean
   - Cómo se procesa la información
   - Quién tiene acceso

2. **Necesidad y proporcionalidad**
   - Por qué es necesario monitorear
   - Alternativas consideradas
   - Medidas de minimización

3. **Riesgos para los empleados**
   - Análisis de privacidad
   - Potencial discriminación
   - Chilling effect (auto-censura)

4. **Medidas de mitigación**
   - Anonimización por diseño
   - Cifrado multicapa
   - Acceso restringido
   - Auditoría externa

---

### **JURISPRUDENCIA ARGENTINA RELEVANTE**

#### **Fallo "Bustos c/ Cablevisión" (2016)**

**Conclusión:**
- ✅ Es legal monitorear emails corporativos
- ✅ SI hay notificación previa
- ✅ SI se limita a comunicaciones laborales
- ❌ NO se puede monitorear cuentas personales

**Aplicación a Overhearing:**
→ El sistema solo monitorea emails con dominio `@empresa.com`, no cuentas personales.

---

#### **Fallo "González c/ OSDE" (2018)**

**Conclusión:**
- ✅ Es legal grabar llamadas telefónicas laborales
- ✅ SI se informa al empleado
- ✅ SI hay cartel de "Esta llamada puede ser grabada"

**Aplicación a Overhearing:**
→ Carteles de notificación en oficinas y avisos en sistemas digitales.

---

#### **Fallo "Rodríguez c/ Telecom" (2020)**

**Conclusión:**
- ❌ NO es legal usar datos de monitoreo para despido disciplinario
- ✅ SOLO si el monitoreo fue notificado y limitado a compliance

**Aplicación a Overhearing:**
→ Los datos del sistema NO pueden usarse directamente para despidos, solo para investigaciones de compliance.

---

## 🔒 ARQUITECTURA TÉCNICA DE PROTECCIÓN

### **1. ANONIMIZACIÓN POR DISEÑO**

#### **Sistema NO guarda:**

```json
❌ PROHIBIDO:
{
  "empleado_id": "EMP-12345",
  "nombre": "Juan Pérez",
  "puesto": "Gerente de Compras",
  "email": "juan.perez@empresa.com",
  "audio_original": "link_a_grabacion_completa.mp3",
  "transcript_completo": "Toda la conversación sin editar",
  "ip_dispositivo": "192.168.1.45",
  "ubicacion_fisica": "Oficina Piso 3, Sala Reuniones A"
}
```

#### **Sistema SÍ guarda (ANONIMIZADO):**

```json
✅ PERMITIDO:
{
  "incidente_id": "OVH-2025-11-0042",
  "tipo": "CONFLICTO_INTERES",
  "fecha": "2025-11-26",
  "hora_aprox": "14:00-16:00", // Ventana de 2 horas
  "area_organizacional": "COMPRAS", // No personas
  "snippet_relevante": "[PERSONA_A]: 'Si le das ese contrato a [FAMILIAR]...'",
  "contexto_minimo": "Conversación sobre licitación [LIC-789]",
  "patron_detectado": "NEPOTISMO",
  "nivel_confianza": 0.87,
  "hash_evidencia": "sha256:abc123..." // Para integridad
}
```

#### **Metadata ELIMINADA automáticamente:**

- ❌ Nombres de participantes
- ❌ Emails individuales
- ❌ Extensiones telefónicas
- ❌ IPs de dispositivos
- ❌ Ubicación física
- ❌ Timestamps exactos (se redondean a ventanas de 2 horas)

---

### **2. MODELO DE PERMISOS (ACCESO RESTRINGIDO)**

```
┌─────────────────────────────────────────────────┐
│ NIVEL 1 - Sistema IA (Automatizado)            │
├─────────────────────────────────────────────────┤
│ ✅ Analiza TODAS las comunicaciones             │
│ ✅ Genera alertas anonimizadas                  │
│ ❌ NO tiene acceso a identidades                │
│ ❌ NO puede desanonimizar                       │
└─────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────┐
│ NIVEL 2 - Compliance Officer                   │
├─────────────────────────────────────────────────┤
│ ✅ Ve alertas anonimizadas                      │
│ ✅ Decide si investigar                         │
│ ❌ NO ve identidades SIN orden de investigación │
│ ❌ Acceso auditado en log inmutable             │
└─────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────┐
│ NIVEL 3 - Investigación Formal                 │
│ (Con aprobación Comité de Ética)               │
├─────────────────────────────────────────────────┤
│ ✅ Desanonimiza SOLO el caso específico         │
│ ✅ Acceso registrado en audit log inmutable     │
│ ✅ Notificación a Comité de Ética               │
│ ✅ Plazo límite (30 días para investigación)    │
│ ✅ Borrado automático tras resolución           │
└─────────────────────────────────────────────────┘
```

#### **Workflow de acceso:**

```
1. IA detecta posible fraude → ALERTA ANÓNIMA

2. Compliance Officer revisa alerta anonimizada
   → Decide: "Parece grave, necesito investigar"

3. Compliance solicita desanonimización
   → Sistema requiere: Aprobación de Comité de Ética

4. Comité de Ética evalúa solicitud
   → Aprueba o rechaza

5. Si aprueba → Sistema desanonimiza SOLO ese caso
   → Registro en audit log: "Usuario X accedió a identidades del caso OVH-0042"

6. Investigación formal
   → Se identifican responsables
   → Acciones correctivas

7. Tras resolución
   → Datos desanonimizados borrados (excepto audit log)
   → Solo queda registro de investigación (sin PII)
```

---

### **3. CIFRADO MULTICAPA**

#### **Datos en tránsito:**

```
Capa 1: TLS 1.3 (HTTPS)
  Empleado → IntegridAI: Certificado SSL/TLS

Capa 2: mTLS (Mutual TLS)
  IntegridAI → Backend: Autenticación mutua con certificados
```

#### **Datos en reposo:**

```
Capa 1: Transparent Data Encryption (TDE)
  Base de datos PostgreSQL con cifrado a nivel de disco

Capa 2: AES-256 (Campos sensibles)
  Snippets de conversaciones, evidencia

Capa 3: GPG para backups
  Backups cifrados con claves asimétricas
```

#### **Gestión de claves:**

```
Almacenamiento: AWS KMS / Azure Key Vault
Rotación: Automática cada 90 días
Acceso: Auditado y restringido
Backup: Claves en cold storage cifrado
```

---

### **4. POLÍTICA DE RETENCIÓN DE DATOS**

| Tipo de dato | Retención | Después | Excepción |
|--------------|-----------|---------|-----------|
| **Audio/Video original** | 7 días | ELIMINADO | Si hay alerta activa: 30 días |
| **Transcripciones completas** | 30 días | ELIMINADAS | Solo se guardan snippets |
| **Alertas anonimizadas** | 2 años | Archivadas sin PII | Compliance Ley 27.401 |
| **Casos investigados** | 5 años | ELIMINADOS | Requisito legal |
| **Audit log** | 10 años | Archivado | Inmutable, solo lectura |

**Eliminación certificada:**
- Borrado criptográfico (destrucción de claves)
- Certificado de eliminación ISO 27001
- Auditoría externa anual

---

### **5. DERECHO DE ACCESO DEL EMPLEADO**

Según **GDPR Art. 15** y **Ley 25.326 Art. 14**, el empleado puede solicitar:

#### **Portal de autoservicio:**

```
1. "Mis datos en el sistema"
   → Ver qué datos se tienen sobre él
   → Categoría: Empleado activo, área, puesto

2. "Historial de accesos"
   → Ver quién accedió a sus datos (si fueron desanonimizados)
   → Fecha, motivo, aprobación

3. "Solicitar corrección"
   → Corregir datos incorrectos
   → Ej: "Mi puesto está mal cargado"

4. "Solicitar eliminación" (Derecho al olvido)
   → Borrar datos no esenciales
   → Excepciones: Casos legales activos, obligación legal
```

---

## 📢 COMUNICACIÓN TRANSPARENTE A EMPLEADOS

### **A. CARTEL DE NOTIFICACIÓN (OBLIGATORIO)**

#### **En oficinas físicas:**

```
┌─────────────────────────────────────────────────┐
│  ⚠️  AVISO: ENTORNO MONITOREADO                 │
│                                                  │
│  Este lugar de trabajo utiliza sistemas         │
│  automatizados de compliance para prevenir      │
│  violaciones al Código de Ética y cumplimiento  │
│  de Ley 27.401.                                  │
│                                                  │
│  Las comunicaciones laborales (emails           │
│  corporativos, reuniones, chat interno) pueden  │
│  ser analizadas con fines de cumplimiento legal.│
│                                                  │
│  Tus datos personales están protegidos por      │
│  cifrado y anonimización.                        │
│                                                  │
│  Más información:                                │
│  compliance@empresa.com                          │
│  Tel: XXXX-XXXX                                  │
└─────────────────────────────────────────────────┘
```

#### **En plataformas digitales:**

Al iniciar sesión en email/chat corporativo:

```
┌─────────────────────────────────────────────────┐
│  ⚠️  RECORDATORIO DE COMPLIANCE                 │
│                                                  │
│  Este sistema está monitoreado con fines de     │
│  compliance (Ley 27.401).                        │
│                                                  │
│  Al continuar, aceptas la Política de Monitoreo.│
│                                                  │
│  [ Ver Política Completa ]  [ Continuar ]       │
└─────────────────────────────────────────────────┘
```

---

### **B. POLÍTICA DE MONITOREO (DOCUMENTO PÚBLICO)**

#### **Contenido mínimo:**

```markdown
# POLÍTICA DE MONITOREO DE COMPLIANCE - [EMPRESA]

## 1. ALCANCE

### Se monitorean comunicaciones laborales en herramientas corporativas:
  - Email corporativo (@empresa.com)
  - Chat interno (Slack/Teams/similar)
  - Reuniones virtuales grabadas (Zoom/Teams)
  - Llamadas telefónicas laborales (extensiones corporativas)

### NO se monitorean:
  ❌ Cuentas de email personales (Gmail, Hotmail, etc.)
  ❌ WhatsApp personal
  ❌ Dispositivos personales (BYOD)
  ❌ Comunicaciones fuera de horario laboral (excepto uso de herramientas corporativas)

## 2. FINALIDAD

El único propósito del monitoreo es:
  ✅ Detectar violaciones al Código de Ética
  ✅ Cumplir con Ley 27.401 (Responsabilidad Penal Empresaria)
  ✅ Prevenir fraude, corrupción, acoso, discriminación

NO se usa para:
  ❌ Evaluación de desempeño
  ❌ Control de productividad
  ❌ Vigilancia de actividad laboral general
  ❌ Decisiones disciplinarias directas (sin investigación formal)

## 3. TECNOLOGÍA

Sistema de IA analiza automáticamente comunicaciones.
Solo genera alertas cuando detecta patrones de riesgo.
Alertas son anonimizadas por defecto.

## 4. PRIVACIDAD

  - Datos anonimizados por defecto
  - Cifrado AES-256
  - Acceso restringido a Compliance Officer
  - Desanonimización solo con aprobación Comité de Ética
  - Audit log de todos los accesos
  - Eliminación automática según política de retención

## 5. TUS DERECHOS

Podés solicitar:
  - Acceso a tus datos (compliance@empresa.com)
  - Corrección de datos inexactos
  - Eliminación de datos (excepto casos legales activos)
  - Historial de accesos a tu información

## 6. PREGUNTAS Y DENUNCIAS

Si tenés dudas o querés denunciar un uso indebido del sistema:
  - Contactá al Compliance Officer: compliance@empresa.com
  - Usá el Canal de Denuncias anónimo: [link]
  - Contactá al Comité de Ética: etica@empresa.com
```

---

### **C. CAPACITACIÓN OBLIGATORIA**

#### **Onboarding (Nuevos empleados):**

**Módulo de 30 minutos:**

1. ¿Por qué monitoreamos?
   - Ley 27.401 (obligación legal)
   - Protección de la empresa y empleados

2. ¿Qué monitoreamos?
   - Solo comunicaciones laborales
   - No cuentas personales

3. ¿Cómo protegemos tu privacidad?
   - Anonimización automática
   - Cifrado multicapa
   - Acceso restringido

4. ¿Qué pasa si se detecta algo?
   - Alerta anonimizada al Compliance Officer
   - Investigación formal (si es necesario)
   - Desanonimización solo con aprobación

5. Tus derechos
   - Acceso, corrección, eliminación
   - Derecho a denunciar uso indebido

**Certificación:**
Quiz de 10 preguntas (80% aprobación)

#### **Refresher Anual:**

**Módulo de 15 minutos:**

- Recordatorio de políticas
- Actualización de normativa
- Casos de estudio (anonimizados)
- Quiz de certificación

---

## 🔍 CONTROLES Y SALVAGUARDAS

### **1. COMITÉ DE ÉTICA INDEPENDIENTE**

#### **Composición:**

- 1 Compliance Officer (empresa)
- 1 Representante de RRHH
- 1 Abogado externo (independiente)
- 1 Representante sindical (si hay sindicato)
- 1 Miembro del directorio

#### **Funciones:**

1. ✅ Aprobar desanonimizaciones
   - Revisar solicitud del Compliance Officer
   - Validar necesidad de investigación
   - Aprobar o rechazar

2. ✅ Revisar casos mensuales
   - Dashboard de alertas (anonimizadas)
   - Identificar patrones de riesgo
   - Recomendar acciones preventivas

3. ✅ Auditar accesos al sistema
   - Revisar audit log mensualmente
   - Identificar accesos no justificados
   - Tomar acciones correctivas

4. ✅ Validar que NO se use para control laboral
   - Revisar finalidad de alertas
   - Asegurar cumplimiento de políticas
   - Sancionar usos indebidos

#### **Reuniones:**

- Mensuales (regulares)
- Ad-hoc (casos urgentes)
- Actas públicas (anonimizadas)

---

### **2. AUDITORÍA EXTERNA ANUAL**

#### **Auditor independiente revisa:**

✅ **Cumplimiento de políticas de privacidad**
- ¿Se respetan las limitaciones de uso?
- ¿Se anonimiza correctamente?

✅ **Finalidad exclusiva de compliance**
- ¿Se usa solo para prevención?
- ¿NO se usa para control laboral o evaluación?

✅ **Política de retención**
- ¿Se eliminan datos según calendario?
- ¿Hay datos obsoletos no borrados?

✅ **Registro de accesos**
- ¿Se registran todos los accesos?
- ¿Hay accesos no justificados?

✅ **Casos de abuso**
- ¿Se ha usado el sistema indebidamente?
- ¿Hay quejas de empleados fundadas?

#### **Resultado:**

**Certificación:**
- ISO 27001 (Seguridad de la Información)
- SOC 2 Type II (Controles de privacidad)

**Reporte público:**
- Resumen ejecutivo (sin detalles sensibles)
- Publicado en intranet corporativa

---

### **3. WHISTLEBLOWING SOBRE EL SISTEMA**

**Ironía importante:** Si un empleado siente que el sistema de overhearing se está usando INDEBIDAMENTE, puede denunciar esto a través del... ¡Canal de Denuncias!

#### **Canal especial:**

```
Categoría: "Denuncia sobre uso indebido de sistemas de monitoreo"

Destino: 
  → Va directo al Comité de Ética (NO al Compliance Officer)
  → Investigación independiente
  → Auditoría externa si es necesario

Protección:
  → Anonimato total
  → Anti-represalias (Ley 27.401 Art. 34)
  → Seguimiento obligatorio
```

---

## 📊 MÉTRICAS DE TRANSPARENCIA

IntegridAI Suite genera un **Reporte Trimestral de Transparencia** público (intranet):

```
┌─────────────────────────────────────────────────┐
│ REPORTE DE TRANSPARENCIA Q3 2026               │
├─────────────────────────────────────────────────┤
│ Comunicaciones analizadas: 150,000             │
│ Alertas generadas (anonimizadas): 23           │
│ Desanonimizaciones aprobadas: 5                │
│ Investigaciones formales: 3                    │
│ Casos confirmados: 2                           │
│ Acciones correctivas: 2                        │
│                                                 │
│ Denuncias sobre uso indebido del sistema: 0    │
│ Auditoría externa: Certificación ISO 27001 ✅  │
└─────────────────────────────────────────────────┘
```

---

## ❓ PREGUNTAS FRECUENTES

### **1. ¿El sistema escucha conversaciones personales?**

❌ **NO.** Solo monitorea:
- Emails corporativos (@empresa.com)
- Chat interno corporativo (Slack/Teams)
- Reuniones virtuales laborales grabadas
- Llamadas telefónicas de extensiones corporativas

NO monitorea:
- WhatsApp personal
- Emails personales (Gmail, Hotmail)
- Llamadas desde celular personal

---

### **2. ¿Quién tiene acceso a mis conversaciones?**

Por defecto: **NADIE.**

El sistema solo genera alertas **anonimizadas**.

Para que alguien vea identidades:
1. El Compliance Officer debe solicitar desanonimización
2. El Comité de Ética debe aprobar
3. El acceso queda registrado en audit log

---

### **3. ¿Pueden despedirme por algo que detectó el sistema?**

❌ **NO directamente.**

El sistema:
- Detecta patrones de riesgo
- Genera alertas anonimizadas
- Inicia investigación formal (si se aprueba)

El despido solo puede resultar de:
- Investigación formal completa
- Due process (derecho a defensa)
- Evidencia adicional (no solo del sistema)

---

### **4. ¿Puedo saber si me están investigando?**

**SÍ.**

Si tus datos son desanonimizados:
- Serás notificado dentro de 48 horas
- Tendrás derecho a defensa
- Podrás acceder al audit log de accesos

---

### **5. ¿Qué pasa si creo que el sistema se está usando mal?**

Podés denunciarlo a través de:
- Canal de Denuncias (categoría "Uso indebido de monitoreo")
- Directamente al Comité de Ética: etica@empresa.com
- Sindicato (si estás afiliado)

La denuncia es anónima y protegida contra represalias (Ley 27.401 Art. 34).

---

### **6. ¿Puedo rechazar el monitoreo?**

**Legalmente:** Sí, podés negarte.

**Consecuencias:**
- No podrás usar herramientas corporativas de comunicación
- Puede limitar tu capacidad de desempeñar ciertas funciones
- La empresa puede tomar decisiones laborales justificadas

**Recomendación:** Hablar con RRHH antes de rechazar.

---

## 🎯 RESUMEN: PRINCIPIOS DE PRIVACIDAD

IntegridAI Suite - Sistema Overhearing se rige por estos principios:

1. **Transparencia Total**
   - Empleados saben que están monitoreados
   - Políticas públicas y accesibles

2. **Anonimización por Diseño**
   - Identidades ocultas por defecto
   - Desanonimización solo con aprobación

3. **Propósito Limitado**
   - Solo compliance (no control laboral)
   - NO se usa para evaluación de desempeño

4. **Minimización de Datos**
   - Solo lo necesario
   - Eliminación automática según política

5. **Cifrado y Seguridad**
   - AES-256 multicapa
   - Certificación ISO 27001

6. **Acceso Restringido**
   - Solo Compliance Officer (con aprobación)
   - Audit log inmutable

7. **Derechos del Empleado**
   - Acceso, corrección, eliminación
   - Derecho a denunciar uso indebido

8. **Auditoría Independiente**
   - Auditor externo anual
   - Certificación SOC 2 Type II

---

## 📞 CONTACTO

Para consultas sobre privacidad o el Sistema Overhearing:

**Compliance Officer:**
compliance@empresa.com

**Comité de Ética:**
etica@empresa.com

**Canal de Denuncias (anónimo):**
[Link al canal]

**IntegridAI Suite - Soporte Técnico:**
support@integridai.com

---

**Documento preparado por:** IntegridAI Suite  
**Versión:** 1.0 (26 Nov 2025)  
**Próxima revisión:** 26 Feb 2026
