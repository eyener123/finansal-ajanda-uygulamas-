# finansal-ajanda-uygulamas-
finansal ajanda visiual studio (wpf form)
<Window x:Class="WpfApp1.MainWindow"
        xmlns="http://schemas.microsoft.com/winfx/2006/xaml/presentation"
        xmlns:x="http://schemas.microsoft.com/winfx/2006/xaml"
        Title="MainWindow" Height="450" Width="800">
    <Grid>
        <Grid.RowDefinitions>
            <RowDefinition Height="170"/>
            <RowDefinition Height="*"/>
        </Grid.RowDefinitions>

        <Grid.ColumnDefinitions>
            <ColumnDefinition Width="220"/>
            <ColumnDefinition Width="*"/>
        </Grid.ColumnDefinitions>

        <!-- Logo buton -->
        <Border Grid.Row="0" Grid.Column="0">
            <Border.Background>
                <ImageBrush ImageSource="C:\Users\lenovo\source\repos\WpfApp1\WpfApp1\icon\1finans.jpeg"/>
            </Border.Background>
            <Grid Background="#FF134187">
                <Grid.RowDefinitions>
                    <RowDefinition Height="35"/>
                    <RowDefinition />
                </Grid.RowDefinitions>

                <!-- Finansal Ajanda Başlığı -->
                <Border Grid.Row="0">
                    <DockPanel HorizontalAlignment="Center">
                        <Image Source="C:\Users\lenovo\source\repos\WpfApp1\WpfApp1\icon\1finans.jpeg" Width="26" Height="26"/>
                        <Label Content="Finansal Ajanda"  
                               Foreground="White" 
                               FontWeight="Bold" 
                               VerticalAlignment="Center" 
                               HorizontalAlignment="Left" 
                               Background="#FF1F467B" 
                               FontSize="14" 
                               FontFamily="Lucida Handwriting"/>
                    </DockPanel>
                </Border>

                <!-- İkon ve Buton -->
                <Border Grid.Row="1">
                    <DockPanel HorizontalAlignment="Center">
                        <Image>
                            <Image.Style>
                                <Style TargetType="Image">
                                    <Setter Property="Source" Value="C:\Users\lenovo\source\repos\WpfApp1\WpfApp1\icon\1finans.jpeg"/>
                                    <Setter Property="Height" Value="auto"/>
                                    <Setter Property="Width" Value="100"/>
                                    <Style.Triggers>
                                        <Trigger Property="IsMouseOver" Value="True">
                                            <Setter Property="Source" Value="C:\Users\lenovo\source\repos\WpfApp1\WpfApp1\icon\1finans.jpeg"/>
                                            <Setter Property="Width" Value="200"/>
                                        </Trigger>
                                    </Style.Triggers>
                                </Style>
                            </Image.Style>
                        </Image>
                    </DockPanel>
                </Border>
            </Grid>
        </Border>

        <!-- Mini butonlar ve header -->
        <Border Background="#FF134187" Grid.Row="0" Grid.Column="1">
            <Grid>
                <Grid.RowDefinitions>
                    <RowDefinition Height="35"/>
                    <RowDefinition />
                </Grid.RowDefinitions>
                <Border Background="White"/>
                <DockPanel Width="70" HorizontalAlignment="Right" Margin="0,0,2,0">
                    <Button Content="-" Width="35" Margin="2,0,0,0"/>
                    <Button Content="x" Width="35" Margin="2,0,2,0"/>
                </DockPanel>
            </Grid>
        </Border>
        <Border Background="#FF134187" Grid.Row="0" Grid.Column="1">
            <Grid>
                <Grid.RowDefinitions>
                    <RowDefinition Height="35"/>
                    <RowDefinition />
                </Grid.RowDefinitions>
                <Border Background="White"/>
                <DockPanel Width="70" HorizontalAlignment="Right" Margin="0,0,2,0">
                    <Button Content="-" Width="35" Margin="2,0,0,0"/>
                    <Button Content="x" Width="35" Margin="2,0,2,0"/>
                </DockPanel>
            </Grid>
        </Border>
        <Border Background="#FF134187" Grid.Row="0" Grid.Column="1">
            <Grid>
                <Grid.RowDefinitions>
                    <RowDefinition Height="35"/>
                    <RowDefinition />
                </Grid.RowDefinitions>
                <Border Background="White"/>
                <DockPanel Width="70" HorizontalAlignment="Right" Margin="0,0,2,0">
                    <Button Content="-" Width="35" Margin="2,0,0,0"/>
                    <Button Content="x" Width="35" Margin="2,0,2,0"/>
                </DockPanel>
            </Grid>
        </Border>
        <Border Background="#FF134187" Grid.Row="0" Grid.Column="1">
            <Grid>
                <Grid.RowDefinitions>
                    <RowDefinition Height="35"/>
                    <RowDefinition />
                </Grid.RowDefinitions>
                <Border Background="White"/>
                <DockPanel Width="70" HorizontalAlignment="Right" Margin="0,0,2,0">
                    <Button Content="-" Width="35" Margin="2,0,0,0"/>
                    <Button Content="x" Width="35" Margin="2,0,2,0"/>
                </DockPanel>
            </Grid>
        </Border>
        <Border Background="#FF134187" Grid.Row="0" Grid.Column="1">
            <Grid>
                <Grid.RowDefinitions>
                    <RowDefinition Height="35"/>
                    <RowDefinition />
                </Grid.RowDefinitions>
                <Border Background="White"/>
                <DockPanel Width="70" HorizontalAlignment="Right" Margin="0,0,2,0">
                    <Button Content="-" Width="35" Margin="2,0,0,0"/>
                    <Button Content="x" Width="35" Margin="2,0,2,0"/>
                </DockPanel>
            </Grid>
        </Border>
        <Border Background="#FF134187" Grid.Row="0" Grid.Column="1">
            <Grid>
                <Grid.RowDefinitions>
                    <RowDefinition Height="35"/>
                    <RowDefinition />
                </Grid.RowDefinitions>
                <Border Background="White"/>
                <DockPanel Width="70" HorizontalAlignment="Right" Margin="0,0,2,0">
                    <Button Content="-" Width="35" Margin="2,0,0,0"/>
                    <Button Content="x" Width="35" Margin="2,0,2,0"/>
                </DockPanel>
            </Grid>
        </Border>
        <Border Background="#FF134187" Grid.Row="0" Grid.Column="1">
            <Grid>
                <Grid.RowDefinitions>
                    <RowDefinition Height="35"/>
                    <RowDefinition />
                </Grid.RowDefinitions>
                <Border Background="White"/>
                <DockPanel Width="70" HorizontalAlignment="Right" Margin="0,0,2,0">
                    <Button Content="-" Width="35" Margin="2,0,0,0"/>
                    <Button Content="x" Width="35" Margin="2,0,2,0"/>
                </DockPanel>
            </Grid>
        </Border>
        <Border Background="#FF134187" Grid.Row="0" Grid.Column="1">
            <Grid>
                <Grid.RowDefinitions>
                    <RowDefinition Height="35"/>
                    <RowDefinition />
                </Grid.RowDefinitions>
                <Border Background="White"/>
                <DockPanel Width="70" HorizontalAlignment="Right" Margin="0,0,2,0">
                    <Button Content="-" Width="35" Margin="2,0,0,0"/>
                    <Button Content="x" Width="35" Margin="2,0,2,0"/>
                </DockPanel>
            </Grid>
        </Border>
        <Border Background="#FF134187" Grid.Row="0" Grid.Column="1">
            <Grid>
                <Grid.RowDefinitions>
                    <RowDefinition Height="35"/>
                    <RowDefinition />
                </Grid.RowDefinitions>
                <Border Background="White"/>
                <DockPanel Width="70" HorizontalAlignment="Right" Margin="0,0,2,0">
                    <Button Content="-" Width="35" Margin="2,0,0,0"/>
                    <Button Content="x" Width="35" Margin="2,0,2,0"/>
                </DockPanel>
            </Grid>
        </Border>
        <Border Background="#FF134187" Grid.Row="0" Grid.Column="1">
            <Grid>
                <Grid.RowDefinitions>
                    <RowDefinition Height="35"/>
                    <RowDefinition />
                </Grid.RowDefinitions>
                <Border Background="White"/>
                <DockPanel Width="70" HorizontalAlignment="Right" Margin="0,0,2,0">
                    <Button Content="-" Width="35" Margin="2,0,0,0"/>
                    <Button Content="x" Width="35" Margin="2,0,2,0"/>
                </DockPanel>
            </Grid>
        </Border>
        <Border Background="#FF134187" Grid.Row="0" Grid.Column="1">
            <Grid>
                <Grid.RowDefinitions>
                    <RowDefinition Height="35"/>
                    <RowDefinition />
                </Grid.RowDefinitions>
                <Border Background="White"/>
                <DockPanel Width="70" HorizontalAlignment="Right" Margin="0,0,2,0">
                    <Button Content="-" Width="35" Margin="2,0,0,0"/>
                    <Button Content="x" Width="35" Margin="2,0,2,0"/>
                </DockPanel>
            </Grid>
        </Border>
        <Border Background="#FF134187" Grid.Row="0" Grid.Column="1">
            <Grid>
                <Grid.RowDefinitions>
                    <RowDefinition Height="35"/>
                    <RowDefinition />
                </Grid.RowDefinitions>
                <Border Background="White"/>
                <DockPanel Width="70" HorizontalAlignment="Right" Margin="0,0,2,0">
                    <Button Content="-" Width="35" Margin="2,0,0,0"/>
                    <Button Content="x" Width="35" Margin="2,0,2,0"/>
                </DockPanel>
            </Grid>
        </Border>
        <Border Background="#FF134187" Grid.Row="0" Grid.Column="1">
            <Grid>
                <Grid.RowDefinitions>
                    <RowDefinition Height="35"/>
                    <RowDefinition />
                </Grid.RowDefinitions>
                <Border Background="White"/>
                <DockPanel Width="70" HorizontalAlignment="Right" Margin="0,0,2,0">
                    <Button Content="-" Width="35" Margin="2,0,0,0"/>
                    <Button Content="x" Width="35" Margin="2,0,2,0"/>
                </DockPanel>
            </Grid>
        </Border>
        <Border Background="#FF134187" Grid.Row="0" Grid.Column="1">
            <Grid>
                <Grid.RowDefinitions>
                    <RowDefinition Height="35"/>
                    <RowDefinition />
                </Grid.RowDefinitions>
                <Border Background="White"/>
                <DockPanel Width="70" HorizontalAlignment="Right" Margin="0,0,2,0">
                    <Button Content="-" Width="35" Margin="2,0,0,0"/>
                    <Button Content="x" Width="35" Margin="2,0,2,0"/>
                </DockPanel>
            </Grid>
        </Border>
        <Border Background="#FF134187" Grid.Row="0" Grid.Column="1">
            <Grid>
                <Grid.RowDefinitions>
                    <RowDefinition Height="35"/>
                    <RowDefinition />
                </Grid.RowDefinitions>
                <Border Background="White"/>
                <DockPanel Width="70" HorizontalAlignment="Right" Margin="0,0,2,0">
                    <Button Content="-" Width="35" Margin="2,0,0,0"/>
                    <Button Content="x" Width="35" Margin="2,0,2,0"/>
                </DockPanel>
            </Grid>
        </Border>
        <Border Background="#FF134187" Grid.Row="0" Grid.Column="1">
            <Grid>
                <Grid.RowDefinitions>
                    <RowDefinition Height="35"/>
                    <RowDefinition />
                </Grid.RowDefinitions>
                <Border Background="White"/>
                <DockPanel Width="70" HorizontalAlignment="Right" Margin="0,0,2,0">
                    <Button Content="-" Width="35" Margin="2,0,0,0"/>
                    <Button Content="x" Width="35" Margin="2,0,2,0"/>
                </DockPanel>
            </Grid>
        </Border>
        <Border Background="#FF134187" Grid.Row="0" Grid.Column="1">
            <Grid>
                <Grid.RowDefinitions>
                    <RowDefinition Height="35"/>
                    <RowDefinition />
                </Grid.RowDefinitions>
                <Border Background="White"/>
                <DockPanel Width="70" HorizontalAlignment="Right" Margin="0,0,2,0">
                    <Button Content="-" Width="35" Margin="2,0,0,0"/>
                    <Button Content="x" Width="35" Margin="2,0,2,0"/>
                </DockPanel>
            </Grid>
        </Border>
        <Border Background="#FF134187" Grid.Row="0" Grid.Column="1">
            <Grid>
                <Grid.RowDefinitions>
                    <RowDefinition Height="35"/>
                    <RowDefinition />
                </Grid.RowDefinitions>
                <Border Background="White"/>
                <DockPanel Width="70" HorizontalAlignment="Right" Margin="0,0,2,0">
                    <Button Content="-" Width="35" Margin="2,0,0,0"/>
                    <Button Content="x" Width="35" Margin="2,0,2,0"/>
                </DockPanel>
            </Grid>
        </Border>
        <Border Background="#FF134187" Grid.Row="0" Grid.Column="1">
            <Grid>
                <Grid.RowDefinitions>
                    <RowDefinition Height="35"/>
                    <RowDefinition />
                </Grid.RowDefinitions>
                <Border Background="White"/>
                <DockPanel Width="70" HorizontalAlignment="Right" Margin="0,0,2,0">
                    <Button Content="-" Width="35" Margin="2,0,0,0"/>
                    <Button Content="x" Width="35" Margin="2,0,2,0"/>
                </DockPanel>
            </Grid>
        </Border>
        <Border Background="#FF134187" Grid.Row="0" Grid.Column="1">
            <Grid>
                <Grid.RowDefinitions>
                    <RowDefinition Height="35"/>
                    <RowDefinition />
                </Grid.RowDefinitions>
                <Border Background="White"/>
                <DockPanel Width="70" HorizontalAlignment="Right" Margin="0,0,2,0">
                    <Button Content="-" Width="35" Margin="2,0,0,0"/>
                    <Button Content="x" Width="35" Margin="2,0,2,0"/>
                </DockPanel>
            </Grid>
        </Border>
        <Border Background="#FF134187" Grid.Row="0" Grid.Column="1">
            <Grid>
                <Grid.RowDefinitions>
                    <RowDefinition Height="35"/>
                    <RowDefinition />
                </Grid.RowDefinitions>
                <Border Background="White"/>
                <DockPanel Width="70" HorizontalAlignment="Right" Margin="0,0,2,0">
                    <Button Content="-" Width="35" Margin="2,0,0,0"/>
                    <Button Content="x" Width="35" Margin="2,0,2,0"/>
                </DockPanel>
            </Grid>
        </Border>
        <Border Background="#FF134187" Grid.Row="0" Grid.Column="1">
            <Grid>
                <Grid.RowDefinitions>
                    <RowDefinition Height="35"/>
                    <RowDefinition />
                </Grid.RowDefinitions>
                <Border Background="White"/>
                <DockPanel Width="70" HorizontalAlignment="Right" Margin="0,0,2,0">
                    <Button Content="-" Width="35" Margin="2,0,0,0"/>
                    <Button Content="x" Width="35" Margin="2,0,2,0"/>
                </DockPanel>
            </Grid>
        </Border> <Border Background="#FF134187" Grid.Row="0" Grid.Column="1">
     <Grid>
         <Grid.RowDefinitions>
             <RowDefinition Height="35"/>
             <RowDefinition />
         </Grid.RowDefinitions>
         <Border Background="White"/>
         <DockPanel Width="70" HorizontalAlignment="Right" Margin="0,0,2,0">
             <Button Content="-" Width="35" Margin="2,0,0,0"/>
             <Button Content="x" Width="35" Margin="2,0,2,0"/>
         </DockPanel>
     </Grid>
 </Border>
        

        <!-- Sol butonlar -->
        <Border Background="#FF134187" Grid.Row="1" Grid.Column="0">
            <StackPanel>
                <Button Height="50" FontSize="16"  FontFamily="HoloLens MDL2 Assets">
                    <DockPanel HorizontalAlignment="Center" Background="#00000000">
                        <Image Source="C:\Users\lenovo\source\repos\WpfApp1\WpfApp1\icon\1finans.jpeg" Width="26"/>
                        <Label Content="Gelir Tablosu" FontFamily="Sitka Display"/>
                    </DockPanel>
                </Button>
            </StackPanel>
        </Border>
        

        <Border Background="#FF134187" Grid.Row="1" Grid.Column="0">
     <StackPanel>
         <Button Height="50" FontSize="16"  FontFamily="HoloLens MDL2 Assets">
             <DockPanel HorizontalAlignment="Center" Background="#00000000">
                 <Image Source="C:\Users\lenovo\source\repos\WpfApp1\WpfApp1\icon\1finans.jpeg" Width="26"/>
                 <Label Content="Gelir Tablosu" FontFamily="Sitka Display"/>
             </DockPanel>
         </Button>
     </StackPanel>
 </Border>
       


        <!-- Sağ içerik alanı -->
        <Border Background="#FF134187" Grid.Row="1" Grid.Column="1">
            <Grid>
                <Grid.ColumnDefinitions>
                    <ColumnDefinition Width="161*"/>
                    <ColumnDefinition Width="419*"/>
                </Grid.ColumnDefinitions>
                <Grid.RowDefinitions>
                    <RowDefinition Height="Auto"/>
                    <RowDefinition />
                </Grid.RowDefinitions>
                <!-- mi buttonlar ve -->
                <Border Background="#FF134187" Grid.Column="0" Grid.Row="1"/>
                


            </Grid>
        </Border>
    </Grid>
</Window>
