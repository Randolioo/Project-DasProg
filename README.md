# Padel Court Booking System

- Program.cs: konfigurasi, konstanta, variabel global, dan Main.
- Menu.cs: menu customer dan admin.
- BranchAndSchedule.cs: pemilihan cabang dan jadwal.
- BookingService.cs: booking, pencarian, validasi jadwal, pembatalan.
- MemberManagement.cs: pengelolaan member.
- Reports.cs: laporan pendapatan.
- InventoryManagement.cs: pengelolaan stok raket dan bola.
- DataStorage.cs: penyimpanan booking dan riwayat inventori.
- InputHelpers.cs: input dan validasi.
- Models.cs: model AppData dan Booking.
- PadelBooking.csproj: konfigurasi .NET 10.

Semua file fitur memakai partial class Program agar dapat berbagi data dan konfigurasi tanpa mengubah alur program.

misal tidak bisa run, ketik `dotnet run` di terminal.
