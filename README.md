# kivy-dasar
# Belajar kivy

"""
Kivy dasar:
Menampilkan label di GUI

Langkah-langkah:
"""

# Mengimport App dari kivy.app
from kivy.app import App

# Import Label untuk menampilkan judul dari kivy.uix.label
from kivy.uix.label import Label


# Buat class aplikasi yang mewarisi dari App yang ada di kivy

class AplikasiKu(App):
	# Buatlah method builder nya
	def build(self):
		"""
		Agar label bisa ditampilkan ke GUI
		maka return nilai labelnya dengan sebuah text
		"""
		return Label(text = 'Selamat datang')  # taks ini yang nanti akan tampil di GUI

# Jalankan aplikasi yang telah dibuat
AplikasiKu().run()




