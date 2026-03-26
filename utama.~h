//---------------------------------------------------------------------------

#ifndef utamaH
#define utamaH
//---------------------------------------------------------------------------
#include <Classes.hpp>
#include <QControls.hpp>
#include <QStdCtrls.hpp>
#include <QForms.hpp>
#include <QComCtrls.hpp>

struct DataKue {
    AnsiString namaKue;
	int stok;
	double hargaKue;
    double keuntungan;
};

struct penjualan {
	AnsiString namaKue;
	int jumlahJual;
	AnsiString namaPelanggan;
	double hargaKue;
	double totalJual;
};
//---------------------------------------------------------------------------
class TForm1 : public TForm
{
__published:	// IDE-managed Components
        TPageControl *PageControl1;
        TTabSheet *TabSheet2;
        TGroupBox *GroupBox2;
        TLabel *Label4;
        TLabel *Label5;
        TLabel *Label6;
        TLabel *Label7;
        TEdit *Edit4;
        TComboBox *ComboBox1;
        TEdit *Edit5;
        TEdit *Edit6;
        TButton *Button2;
        TGroupBox *GroupBox3;
        TListBox *ListBox1;
        TGroupBox *GroupBox6;
        TTabSheet *TabSheet3;
        TTabSheet *TabSheet5;
        TGroupBox *GroupBox7;
        TGroupBox *GroupBox8;
        TGroupBox *GroupBox5;
        TTabSheet *TabSheet1;
        TGroupBox *GroupBox1;
        TGroupBox *GroupBox4;
        TGroupBox *GroupBox10;
        TRadioButton *RadioButton1;
        TRadioButton *RadioButton2;
        TListBox *ListBox2;
        TListBox *ListBox3;
        TRadioButton *RadioButton4;
        TRadioButton *RadioButton5;
        TLabel *Label1;
        TEdit *Edit1;
        TLabel *Label2;
        TEdit *Edit2;
        TButton *Button1;
        TListBox *ListBox4;
        TLabel *Label3;
        TEdit *Edit3;
        TLabel *Label8;
        TEdit *Edit7;
        TLabel *Label9;
        TEdit *Edit8;
       
private:	// User declarations
    DataKue daftarKue[10];
    penjualan penjualanKue[10];

  
    void __fastcall TForm1::PerbaruiListBox();
    void __fastcall TForm1::PerbaruiListPenjualan();
    void __fastcall TForm1::cariHargaKue();
    void __fastcall TForm1::callCariPelanggan();
public:		// User declarations
        __fastcall TForm1(TComponent* Owner);
};
//---------------------------------------------------------------------------
extern PACKAGE TForm1 *Form1;
//---------------------------------------------------------------------------
#endif
