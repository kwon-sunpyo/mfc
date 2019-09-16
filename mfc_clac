# 일단 기본 작업으로 값 입력창 3개와 버튼 두개가 필요합니다.
# 그리고 값 입력창에 변수 이름을 설정해주어야합니다. 변수 설정방법은 변수를 설정하고 싶은 곳에
# 우클릭 후 변수추가를 누른뒤 이름을 바꾸어 주시면됩니다.

void Cclaclater2Dlg::OnBnClickedButton1()
{
	UpdateData(true);
	m_C3 = m_C2 + m_C1;
	UpdateData(false);
}

# 이부분은 ID부분을 바꿀수있는데 저는 IDC_C1로 바꾸었습니다. GetDlgItemInt는 값을 int형태로 가져오며
# SetDlgItemInt는 int 값을 넣어주는 역할을 합니다.

void Cclaclater2Dlg::OnBnClickedD2()
{
	int a = GetDlgItemInt(IDC_C1);
	int b = GetDlgItemInt(IDC_C2);
	int c = a+b;
	SetDlgItemInt(IDC_C3, c);
}
