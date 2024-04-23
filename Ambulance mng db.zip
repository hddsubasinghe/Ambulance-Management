using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;

namespace Ambulance_mng_db
{
    public partial class Form3 : Form
    {
        public Form3()
        {
            InitializeComponent();
        }

        private void detailsBindingNavigatorSaveItem_Click(object sender, EventArgs e)
        {
            this.Validate();
            this.detailsBindingSource.EndEdit();
            this.tableAdapterManager.UpdateAll(this.detailsDataSet1);

        }

        private void Form3_Load(object sender, EventArgs e)
        {
            // TODO: This line of code loads data into the 'detailsDataSet1.Details' table. You can move, or remove it, as needed.
            this.detailsTableAdapter.Fill(this.detailsDataSet1.Details);

        }
    }
}
