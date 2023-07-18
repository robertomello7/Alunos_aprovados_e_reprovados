using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;

namespace WindowsFormsApp5
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }

        private void btnCalcular_Click(object sender, EventArgs e)
        {
            double N1 = double.Parse(tbxNota1.Text);
            double N2 = double.Parse(tbxNota2.Text);
            double N3 = double.Parse(tbxNota3.Text);
            double media = (N1 + N2 +  N3) / 3;
            
            if (media >= 7) { lblResultado.Text = "O aluno está aprovado";}
            if (media < 7) { lblResultado.Text = "O aluno está reprovado";}

            

            
        }
    }
}
