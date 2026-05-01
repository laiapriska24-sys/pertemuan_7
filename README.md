# MyTaskLiistApp - Pemrograman Mobile Pertemuan 7

## Nama & NIM
- Nama: [Priska laia]
- NIM:  [243303621230]

## Fitur yang Diimplementasikan
- Setup & RunningProject dibuat dengan npx create-expo-app, dijalankan via Expo Go
- Komponen DasarMenggunakan View, Text, TextInput, TouchableOpacity, ScrollView, SafeAreaView
- StyleSheet & FlexboxSemua style menggunakan StyleSheet.create(), layout dengan Flexbox
- State ManagementuseState untuk tasks, filter, form input; useMemo untuk data turunan
- Conditional RenderingEmpty state berbeda per filter, badge selesai, strip prioritas, catatan tampil hanya jika ada isi
- TextInput + ValidasiInput nama task wajib diisi, minimal 3 karakter, maksimal 120 karakter; pesan error ditampilkan
- KeyboardAvoidingViewKeyboard tidak menutupi input di iOS maupun Android
- FlatListMenampilkan daftar task dengan keyExtractor dan ListEmptyComponent
- Add TaskMenambah task baru ke daftar
- Delete TaskMenghapus task dengan konfirmasi Alert

## Screenshot/Video



 
[



https://github.com/user-attachments/assets/081219f5-addb-4892-99a4-a571cfc002f5


]

### Tampilan  utama
[<img width="730" height="1600" alt="pertemuan7 2026-05-01 at 12 09 49" src="https://github.com/user-attachments/assets/abb5684b-7dad-47c2-84af-e98bf9fd2e10" />
]



## Cara Menjalankan
1. Clone repo  : git clone [https://snack.expo.dev/@priskalaiacio/f1234a]
2. Install deps: npm install
3. Jalankan    : npx expo start
4. Scan QR Code dengan Expo Go di HP
