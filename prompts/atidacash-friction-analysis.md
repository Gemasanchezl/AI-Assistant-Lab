# 🔍 Análisis de Fricción: Atida Cash en Basket

## 📊 Datos de Entrada

**Feedback de Usuarios:**
- "I saw something about Atida Cash but wasn't sure if I could use it right away."
- "It looks interesting but I didn't understand how much I'd earn."

**Analytics:**
- 62% de usuarios hacen hover sobre el tooltip
- Solo 18% hacen click en el tooltip

---

## 🎯 Principales Puntos de Fricción

### **Patterns (Patrones)**

1. **Incertidumbre sobre disponibilidad inmediata**
   - Los usuarios ven Atida Cash pero no saben si pueden usarlo en el momento actual
   - Hay confusión entre "ganar" y "usar" Atida Cash

2. **Falta de claridad en el valor económico**
   - Los usuarios no comprenden cuánto ganarán específicamente
   - El valor numérico no es evidente a primera vista

3. **Alta curiosidad, baja acción**
   - 62% de hover indica interés y necesidad de información
   - Solo 18% de clicks sugiere que el tooltip no resuelve la duda o no es suficientemente claro

4. **Barrera de comprensión en el primer contacto**
   - Los usuarios necesitan información pero no la encuentran de forma inmediata
   - El tooltip requiere interacción adicional que muchos usuarios no completan

---

### **Learnings (Aprendizajes)**

1. **El tooltip no está resolviendo el gap de comprensión**
   - La alta tasa de hover (62%) muestra que los usuarios buscan información
   - La baja tasa de click (18%) indica que el tooltip no es suficientemente atractivo o claro para justificar el click
   - Posiblemente el contenido del tooltip no responde directamente a las preguntas clave

2. **Falta de transparencia en el valor inmediato**
   - Los usuarios necesitan ver el valor numérico sin interacción adicional
   - La información sobre cuánto ganarán debería ser visible de forma estática

3. **Confusión entre estados: ganar vs. usar**
   - Los usuarios no distinguen claramente si pueden usar Atida Cash ahora o solo ganarlo
   - El copy actual no diferencia entre "earning" y "redeeming"

4. **El diseño actual crea fricción cognitiva**
   - Requiere múltiples pasos mentales: ver → hover → click → leer → comprender
   - Los usuarios abandonan el proceso antes de obtener la información que necesitan

---

### **Next Steps (Próximos Pasos)**

1. **Hacer el valor visible de forma estática**
   - Mostrar el valor numérico ("Ganarás €X") directamente en el componente, sin necesidad de tooltip
   - A/B test: información inline vs. tooltip-only

2. **Clarificar el estado de disponibilidad**
   - Distinguir visualmente entre "Ganarás X€" (futuro) y "Tienes X€ disponibles" (presente)
   - Usar copy más directo: "Ganarás €X en esta compra" o "Usa tus €X de Atida Cash"

3. **Rediseñar el tooltip o eliminarlo**
   - Si se mantiene el tooltip, hacerlo más informativo en el hover (sin necesidad de click)
   - Considerar un tooltip que muestre información clave en hover y detalles adicionales en click
   - Alternativa: eliminar el tooltip y mostrar toda la información relevante inline

4. **Explorar microinteracciones dinámicas**
   - Mostrar la acumulación de Atida Cash de forma visual y dinámica
   - Usar animaciones sutiles que muestren el valor que se ganará

5. **Test de claridad del copy**
   - Probar variaciones de copy que separen claramente "ganar" de "usar"
   - Incluir ejemplos numéricos concretos en el copy principal

---

## 📈 Métricas Clave a Monitorear

- Tasa de conversión de hover a click (actualmente: 18/62 = 29%)
- Comprensión del valor: % de usuarios que pueden identificar cuánto ganarán sin interacción
- Tasa de uso de Atida Cash después de ver la información
- Reducción en preguntas de soporte relacionadas con Atida Cash

