
import tkinter as tk
import random
import math

# ---------------- CONFIGURACIÓN ----------------

ventana = tk.Tk()
ventana.title("Para alguien muy especial ❤️")
ventana.geometry("800x650")
ventana.configure(bg="#160d20")
ventana.resizable(False, False)

canvas = tk.Canvas(
    ventana,
    width=800,
    height=650,
    bg="#160d20",
    highlightthickness=0
)
canvas.pack()

# ---------------- CORAZONES ANIMADOS ----------------

corazones = []

for _ in range(35):
    x = random.randint(0, 800)
    y = random.randint(0, 650)
    velocidad = random.uniform(0.5, 2)
    tamano = random.randint(10, 22)

    corazon = canvas.create_text(
        x, y,
        text="♥",
        fill=random.choice(["#ff4d88", "#ff85a2", "#d94b91"]),
        font=("Arial", tamano)
    )

    corazones.append((corazon, velocidad))

def animar_corazones():
    for corazon, velocidad in corazones:
        canvas.move(corazon, 0, -velocidad)

        x, y = canvas.coords(corazon)

        if y < -20:
            canvas.coords(
                corazon,
                random.randint(0, 800),
                670
            )

    ventana.after(30, animar_corazones)


# ---------------- TÍTULO ----------------

canvas.create_text(
    400, 65,
    text="Quiero pedirte perdón...",
    fill="#ffb6cf",
    font=("Georgia", 29, "bold")
)

canvas.create_text(
    400, 110,
    text="Hay algo que necesito decirte desde el corazón.",
    fill="#ffffff",
    font=("Georgia", 13)
)

# ---------------- ROSA ----------------

canvas.create_text(
    400, 190,
    text="🌹",
    font=("Arial", 75)
)

# ---------------- CARTA ----------------

canvas.create_rectangle(
    105, 255, 695, 490,
    fill="#29172e",
    outline="#e88bab",
    width=2
)

mensaje = (
    "Mi amor...\n\n"
    "Quiero pedirte perdón por las cosas que hice mal,\n"
    "por aquello que pudo lastimarte y por los momentos\n"
    "en los que no supe actuar de la mejor manera.\n\n"
    "No quiero que pienses que no me importas,\n"
    "porque significas muchísimo para mí.\n\n"
    "Sé que decir perdón no cambia lo sucedido,\n"
    "pero quiero demostrarte con hechos que puedo\n"
    "aprender, mejorar y cuidar mucho más lo nuestro.\n\n"
    "No eres alguien más en mi vida.\n"
    "Eres alguien a quien quiero seguir eligiendo. ❤️"
)

texto = canvas.create_text(
    400, 370,
    text="",
    fill="#fff0f5",
    font=("Georgia", 13),
    justify="center",
    width=550
)

indice = 0

def escribir_mensaje():
    global indice

    if indice <= len(mensaje):
        canvas.itemconfig(
            texto,
            text=mensaje[:indice]
        )
        indice += 1
        ventana.after(45, escribir_mensaje)


# ---------------- BOTÓN ----------------

def perdon():
    canvas.delete("sorpresa")

    canvas.create_rectangle(
        100, 250, 700, 500,
        fill="#3b1835",
        outline="#ff9cbd",
        width=3,
        tags="sorpresa"
    )

    canvas.create_text(
        400, 305,
        text="❤️ Gracias por leerme ❤️",
        fill="#ffb6cf",
        font=("Georgia", 23, "bold"),
        tags="sorpresa"
    )

    canvas.create_text(
        400, 380,
        text="No te prometo ser perfecto,\n"
             "pero sí seguir aprendiendo a amarte mejor.\n\n"
             "Quiero que lo nuestro siga teniendo\n"
             "muchas páginas bonitas por escribir. 💗",
        fill="white",
        font=("Georgia", 15),
        justify="center",
        tags="sorpresa"
    )

    canvas.create_text(
        400, 455,
        text="Te quiero muchísimo. ❤️",
        fill="#ff85ad",
        font=("Georgia", 17, "bold"),
        tags="sorpresa"
    )

boton = tk.Button(
    ventana,
    text="¿Me perdonas? 🥺❤️",
    command=perdon,
    font=("Arial", 15, "bold"),
    bg="#e84c85",
    fg="white",
    activebackground="#ff80aa",
    activeforeground="white",
    relief="flat",
    cursor="hand2",
    padx=25,
    pady=12
)

canvas.create_window(400, 550, window=boton)

canvas.create_text(
    400, 615,
    text="Hecho con mucho amor ❤️",
    fill="#b88ca8",
    font=("Georgia", 10, "italic")
)

# ---------------- INICIAR ----------------

animar_corazones()
ventana.after(1000, escribir_mensaje)

ventana.mainloop()
