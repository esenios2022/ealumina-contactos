# 🔧 Arreglar Error RLS en Supabase

## Problema
Tu tabla `contactos` tiene **Row-Level Security (RLS)** activado, lo que impide guardar contactos.

---

## Solución

### Paso 1: Entra a Supabase
1. Ve a [app.supabase.com](https://app.supabase.com)
2. Haz login con tu cuenta
3. Selecciona tu proyecto `udtenqjlofjduuwffjja`

### Paso 2: Abre SQL Editor
1. En el menú izquierdo, busca **"SQL Editor"** (o **"Editor SQL"**)
2. Haz clic en él

### Paso 3: Copia este comando

```sql
ALTER TABLE public.contactos DISABLE ROW LEVEL SECURITY;
```

### Paso 4: Pega el comando
1. En el área de texto del SQL Editor, **borra todo lo que hay**
2. **Pega el comando** que copiaste arriba
3. Debería verse así:
   ```
   ALTER TABLE public.contactos DISABLE ROW LEVEL SECURITY;
   ```

### Paso 5: Ejecuta el comando
1. Haz clic en el botón **"Run"** (o **"Execute"**)
2. Espera 2-3 segundos

### Paso 6: Verifica que funcionó
- Deberías ver un mensaje: **"Success"** o **"Query executed successfully"**
- Si ves un error, copia el mensaje exacto y pégamelo

---

## ¡Listo!

Una vez que veas **"Success"**, vuelve a la página y prueba agregar un contacto de nuevo. Debería funcionar ✅

---

**Si tienes dudas, copia y pega exactamente lo que ves en Supabase después de hacer clic en "Run"** 📋
