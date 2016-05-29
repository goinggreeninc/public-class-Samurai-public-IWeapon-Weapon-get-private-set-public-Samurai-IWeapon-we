public class WarriorModule : NinjectModule
{
    public override void Load() 
    {
        this.Bind<IWeapon>().To<Sword>();
    }
}
