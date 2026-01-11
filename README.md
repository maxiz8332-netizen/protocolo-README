# 🚀 PROTOCOLO APEX v2.0

Optimización de ingeniería para navegadores Chromium (**Chrome, Edge, Brave**). Diseñado para reducir el consumo de recursos y mejorar la latencia del sistema.

---

## 🛠️ Configuración Rápida (Flags)

Escribe `chrome://flags` en tu barra de direcciones, busca los siguientes parámetros y cámbialos a **Enabled**:

* **`enable-parallel-downloading`** -> Descargas más rápidas mediante múltiples paquetes.
* **`enable-gpu-rasterization`** -> Mueve la carga del CPU a la gráfica para mayor fluidez.
* **`enable-skia-graphite`** -> Activa el motor de renderizado de nueva generación.
* **`high-efficiency-mode-available`** -> Habilita el modo de ahorro de memoria avanzado.

> 💡 **Nota:** Es necesario reiniciar el navegador para que los cambios surtan efecto.

---

## 🛡️ Manual de Emergencia (SAFETY)

Si experimentas parpadeos, colores extraños o el navegador no inicia, sigue estos pasos:

1.  **Reset Total:** Si el navegador abre, ve a `chrome://flags` y pulsa el botón **"Reset all"** (arriba a la derecha).
2.  **Modo de Rescate (Sin GPU):** Si el navegador NO abre, presiona `Win + R`, escribe el siguiente comando y pulsa Enter:
    * `chrome.exe --disable-gpu` (o `msedge.exe --disable-gpu` si usas Edge).
3.  **Restauración de Perfil:** Si los errores persisten, ve a la carpeta de datos de usuario y renombra la carpeta `Default` a `Default_old`. Esto creará un perfil limpio.

---

## 📊 ¡Comparte tus resultados!

¿Cuánta RAM lograste ahorrar? Abre el administrador de tareas del navegador (`Shift + Esc`) y cuéntanos tus resultados en la pestaña de **Issues**.

¡Gracias por usar el Protocolo Apex! ⭐
