unit View.principal;

interface

uses
  Winapi.Windows, Winapi.Messages, System.SysUtils, System.Variants, System.Classes, Vcl.Graphics,
  Vcl.Controls, Vcl.Forms, Vcl.Dialogs, Vcl.StdCtrls, Vcl.ExtCtrls, Vcl.Buttons,
  Vcl.Imaging.pngimage;

type
  TForm1 = class(TForm)
    Panel1: TPanel;
    Panel2: TPanel;
    Panel3: TPanel;
    Panel6: TPanel;
    Panel7: TPanel;
    Panel8: TPanel;
    Label1: TLabel;
    Label2: TLabel;
    Panel9: TPanel;
    Label4: TLabel;
    Label3: TLabel;
    Panel11: TPanel;
    Panel10: TPanel;
    Panel12: TPanel;
    Image1: TImage;
    Panel13: TPanel;
    Label5: TLabel;
    Label6: TLabel;
    Panel4: TPanel;
    Panel5: TPanel;
    Panel14: TPanel;
    Panel15: TPanel;
    Label7: TLabel;
    Label8: TLabel;
    Panel16: TPanel;
    Panel17: TPanel;
    Shape1: TShape;
    Shape2: TShape;
    Panel18: TPanel;
    SpeedButton2: TSpeedButton;
    SpeedButton3: TSpeedButton;
    SpeedButton4: TSpeedButton;
    SpeedButton1: TSpeedButton;
    SpeedButton5: TSpeedButton;
    SpeedButton7: TSpeedButton;
    procedure SpeedButton7Click(Sender: TObject);
    procedure SpeedButton2Click(Sender: TObject);
    procedure SpeedButton3Click(Sender: TObject);
    procedure SpeedButton4Click(Sender: TObject);
    procedure SpeedButton5Click(Sender: TObject);
    procedure SpeedButton1Click(Sender: TObject);
    procedure Label1MouseEnter(Sender: TObject);
    procedure Label1MouseLeave(Sender: TObject);
  private
    procedure GET_LineMenu(sender: TObject);
  public
    { Public declarations }
  end;

var
  Form1: TForm1;

implementation

{$R *.dfm}

procedure TForm1.GET_LineMenu(sender: TObject);
begin
  Shape1.Left := 0;
  Shape1.Left := TSpeedButton(Sender).Height;
  Shape1.Top  := TSpeedButton(Sender).Top;
  Shape1.Repaint;

end;

procedure TForm1.Label1MouseEnter(Sender: TObject);
begin
  Label1.Font.Color := $000fbbd9;
end;

procedure TForm1.Label1MouseLeave(Sender: TObject);
begin
   Label1.Font.Color := clWhite;
end;

procedure TForm1.SpeedButton1Click(Sender: TObject);
begin
  GET_LineMenu(Sender);
end;

procedure TForm1.SpeedButton2Click(Sender: TObject);
begin
 GET_LineMenu(Sender);
end;

procedure TForm1.SpeedButton3Click(Sender: TObject);
begin
  GET_LineMenu(Sender);
end;

procedure TForm1.SpeedButton4Click(Sender: TObject);
begin
  GET_LineMenu(Sender);
end;

procedure TForm1.SpeedButton5Click(Sender: TObject);
begin
  GET_LineMenu(Sender);
end;

procedure TForm1.SpeedButton7Click(Sender: TObject);
begin
  Application.Terminate;
end;

end.
