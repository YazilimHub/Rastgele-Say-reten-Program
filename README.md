Rastgele Sayı Üreten Program


        private void button1_Click(object sender, EventArgs e)
        {
            Random rnd = new Random();
            listBox1.Items.Add(Convert.ToInt32(rnd.Next(0, 9)));
        }

        private void button2_Click(object sender, EventArgs e)
        {
            Random rnd = new Random();
            listBox2.Items.Add(Convert.ToInt32(rnd.Next(10, 99)));
        }

        private void button3_Click(object sender, EventArgs e)
        {
            Random rnd = new Random();
            listBox3.Items.Add(Convert.ToInt32(rnd.Next(100, 999)));
        }

        private void button4_Click(object sender, EventArgs e)
        {
            Random rnd = new Random();
            listBox4.Items.Add(Convert.ToInt32(rnd.Next(1000, 9999)));
        }

        private void button5_Click(object sender, EventArgs e)
        {
            Random rnd = new Random();
            listBox5.Items.Add(Convert.ToInt32(rnd.Next(10000, 99999)));
        }

        private void button6_Click(object sender, EventArgs e)
        {
            listBox1.Items.Clear();
            listBox2.Items.Clear();
            listBox3.Items.Clear();
            listBox4.Items.Clear();
            listBox5.Items.Clear();
        }
