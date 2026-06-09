# Título Principal (H1)

## Subtítulo (H2)

### Sección (H3)

#### Subsección (H4)

---

**Texto en negrita**

*Texto en cursiva*

> Esto es una cita o nota importante.

---

## Lista

- Elemento 1
- Elemento 2
- Elemento 3

---

## Lista Numerada

1. Paso 1
2. Paso 2
3. Paso 3

---

## Tabla

| Activo | Estado | Riesgo |
|---------|---------|---------|
| dominio.com | Activo | Bajo |
| servidor01 | Activo | Alto |

---

## Comando Bash

```bash
nmap -sV -Pn dominio.com
```

## Comando PowerShell

```powershell
Get-ADUser -Filter *
```

## Comando SQL

```sql
SELECT *
FROM usuarios
WHERE estado = 'activo';
```

## Salida de Comando

```text
22/tcp   open   ssh
80/tcp   open   http
443/tcp  open   https
```

---

## Hallazgo

### Severidad

🔴 Alta

### Descripción

Se encontró un servicio expuesto a Internet.

### Evidencia

```text
22/tcp open ssh OpenSSH 8.9
```

### Recomendación

- Restringir acceso mediante firewall.
- Implementar MFA.
- Actualizar versión.

---

## Indicadores

| Nivel | Cantidad |
|---------|---------|
| 🔴 Crítico | 0 |
| 🟠 Alto | 2 |
| 🟡 Medio | 4 |
| 🟢 Bajo | 8 |

---

## Conclusión

Se identificaron vulnerabilidades que requieren mitigación para reducir la superficie de ataque.
